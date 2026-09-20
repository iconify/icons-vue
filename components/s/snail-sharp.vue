<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jll5tivgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:snail-sharp" /></template>
<style>
.jll5tivgk {
  fill: currentColor;
  d: path("M4 19.02q0-1.324.747-2.4q.747-1.078 1.93-1.658q-1.235-.45-1.956-1.566Q4 12.281 4 10.885q0-2.458 1.788-4.171T10.173 5q1.746 0 3.205.849t2.209 2.315q.28-1.01 1.13-1.616t1.931-.606q1.287 0 2.32.633T22 8.364q0 .905-.652 1.547q-.652.643-1.557.643h-.618v4.254q0 1.773-1.26 2.992t-3.029 1.22zm4.289-4.712q1.384 0 2.355-.876t.971-2.124q0-.812-.419-1.33q-.419-.517-1.077-.517q-.558 0-.954.346q-.396.345-.396.847h-1q0-.904.692-1.548t1.66-.645q1.09 0 1.792.825t.702 2.022q0 .898-.4 1.681q-.4.784-1.092 1.319h2.358q.76 0 1.303-.531t.543-1.296v-1.404q0-2.114-1.51-3.595T10.172 6Q7.996 6 6.498 7.424T5 10.884q0 1.43.949 2.427t2.34.997");
}

</style>
