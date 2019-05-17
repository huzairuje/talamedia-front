<template>
  <nav class="navbar navbar-expand-md bg-white relative">
    <div class="container">
      <div class="col-1 pl-0">
        <a href="/?utm_source=Talamedia&utm_medium=LogoTalamedia">
          <img
            src="/talamedia.png"
            width="45px"
            style="position: absolute; top: 50%; transform: translateY(-50%); left: -15px"
          >
        </a>
      </div>
      <div id="navbarsExampleDefault" class="collapse navbar-collapse">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item">
            <a href="/search" class="nav-link">
              <i class="fa fa-search"></i>
            </a>
          </li>
          <li class="nav-item active">
            <a class="nav-link explore button nava-link">
              Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <nuxt-link to="/info-kampus" class="nav-link">Info Kampus</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/ruang-kota" class="nav-link">Ruang Kota</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/trifantasia" class="nav-link">Trifantasia</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/wedding-wfi" class="nav-link">Wedding From Indonesia</nuxt-link>
          </li>
        </ul>
        <div>
          <div class="my-2 my-lg-0 d-sm-*">
           Space For Ads
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
@keyframes zoominout-data-v-4ecbf65e {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
  25% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  }
  50% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
  75% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  }
  to {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
}
.gambarstories {
    width: 40px;
    height: 40px;
    border-radius: 100%;
    position: absolute;
    cursor: pointer;
}
.zoominout {
    -webkit-animation: zoominout-data-v-4ecbf65e;
    -webkit-animation-duration: 3s;
    -webkit-animation: zoominout-data-v-4ecbf65e 100s infinite;
    animation: zoominout-data-v-4ecbf65e 100s infinite;
    animation-duration: 3s;
}
.border {
    width: 46px;
    height: 46px;
    border-radius: 100%;
    background-color: #f2bdf2;
    position: absolute;
    background-image: -webkit-gradient(linear,right top,left bottom,from(#c82d8d),to(#f99e4d));
    background-image: linear-gradient(to left bottom,#c82d8d 0,#f99e4d);
}
.border, .container-fotostories {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -ms-flex-flow: row nowrap;
    flex-flow: row nowrap;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -ms-flex-line-pack: center;
    align-content: center;
}
</style>
