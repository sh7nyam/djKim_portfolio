<template>
  <div id="app">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand mainStyle " href="#">My Portfolio</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav-collapse">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse " id="nav-collapse">
          <ul class="navbar-nav me-auto text-dark">
            <li class="nav-item leftMargin">
              <a class="nav-link text-dark" href="#profile">Profile</a>
            </li>
            <li class="nav-item leftMargin">
              <a class="nav-link text-dark" href="#skills">Skills</a>
            </li>
            <li class="nav-item leftMargin">
              <a class="nav-link text-dark" href="#certifications">Certifications</a>
            </li>
            <li class="nav-item leftMargin">
              <a class="nav-link text-dark" href="#projects">Projects</a>
            </li>
          </ul>
        </div>
      </nav>

      <div class="container mt-5">
        <div class="row">
          <div class="col">
            <!-- todo: 프로필 -->
            <section id="profile" class="my-5">
              <div class="card profile-card">
                <div class="card-body">
                  <h2 class="card-title">Profile</h2>

                  <p class="card-text me-3">
                    이름 KIM DONG JU<br>
                    <br>
                    생년월일 1998.07.04<br>
                    <br>
                    최종학력 한국방송통신대학교 컴퓨터과학과 4학년 (휴학)<br>
                    * 1학기만 남은 상태이며, 방통대는 전체 온라인수업으로 진행합니다.<br>

                  </p>
                  <p class="card-text">
                    경력
                    
                  </p>
                </div>
              </div>
            </section>
            <!-- todo : 스킬 -->
            <section id="skills" class="my-5">
              <div class="card skills-card">
                <div class="card-body">
                  <h2 class="card-title">Skills</h2>
                  <ul class="card-text">
                    <li>JavaScript</li>
                    <li>Vue.js</li>
                    <li>HTML/CSS</li>
                    <li>Node.js</li>
                    <li>Python</li>
                  </ul>
                </div>
              </div>
            </section>
            <!-- todo: 자격증 -->
            <section id="certifications" class="my-5">
              <div class="card certifications-card">
                <div class="card-body">
                  <h2 class="card-title">Certifications</h2>
                  <ul class="card-text">
                    <li>Certified JavaScript Developer</li>
                    <li>Certified Vue.js Specialist</li>
                    <li>Certified Python Programmer</li>
                  </ul>
                </div>
              </div>
            </section>
            <!-- todo: 팀프로젝트 -->
            <section id="projects" class="my-5">
              <div class="card projects-card">
                <div class="card-body">
                  <h2 class="card-title">Projects</h2>
                  <ul class="card-text">
                    <li>
                      <h3>Project 1</h3>
                      <p>Description of project 1.</p>
                    </li>
                    <li>
                      <h3>Project 2</h3>
                      <p>Description of project 2.</p>
                    </li>
                    <li>
                      <h3>Project 3</h3>
                      <p>Description of project 3.</p>
                    </li>
                  </ul>
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>

      <footer class="text-center mt-5">
        <p>&copy; 2024 My Portfolio</p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>

.mainStyle{
  margin-left: 2vw;
  font-size: large;
}
.leftMargin{
  text-align: center;
  font-weight: 800;
  margin-left: 1vw;
  width: 10vw;
}
body {
  font-family: Arial, sans-serif;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  position: fixed;
  bottom: 0;
  width: 100%;
}

h2 {
  margin-bottom: 1rem;
}

.card {
  margin-bottom: 2rem;
}

.profile-card {
  background-color: #f8f9fa;
  border-left: 4px solid #007bff;
  padding: 1rem;
}

.skills-card {
  background-color: #f8f9fa;
  border-left: 4px solid #28a745;
  padding: 1rem;
}

.certifications-card {
  background-color: #f8f9fa;
  border-left: 4px solid #ffc107;
  padding: 1rem;
}

.projects-card {
  background-color: #f8f9fa;
  border-left: 4px solid #17a2b8;
  padding: 1rem;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  background: #e9ecef;
  margin: 0.5rem 0;
  padding: 0.5rem;
  border-radius: 4px;
}

ul li h3 {
  margin: 0;
}
</style>
