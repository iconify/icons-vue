<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmrjf0wih"/><circle class="o8j62sbtn"/><path class="n1949171i"/><circle class="u9ssrlu1o"/><path class="gvc3pacef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:python" /></template>
<style>
.gvc3pacef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.895 31.98c1.728 8.685-3.766 9.684-9.076 9.606c-4.77-.07-9.394-.48-9.359-6.068v-5.414c.062-4.894 1.764-6.054 6.159-6.12l6.762.032c4.395-.066 6.097-1.226 6.159-6.12v-5.413c.035-5.588-4.589-5.999-9.36-6.069c-5.309-.077-10.803.921-9.075 9.607");
}

.n1949171i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.82 31.98h12.01c5.42-.181 6.761-3.574 6.665-7.976c-.172-7.895-2.145-10.173-8.955-10.245");
}

.o8j62sbtn {
  cx: 19.264px;
  cy: 10.678px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u9ssrlu1o {
  cx: 28.736px;
  cy: 37.322px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zmrjf0wih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.18 16.02H12.17c-5.42.181-6.761 3.574-6.665 7.976c.172 7.895 2.145 10.173 8.955 10.245");
}

</style>
