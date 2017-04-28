<template >
  <div>
    <router-link v-if="$route.path !== '/time-entries/log-time'"
    to="/time-entries/log-time"
    class="btn btn-primary">创建
    </router-link>

    <div v-if="$route.path === '/time-entries/log-time'">
      <h3>创建</h3>
    </div>

    <hr>
    <router-view></router-view>
  </div>
</template>
