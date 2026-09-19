<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bs7nw-m1f"/><circle class="h59g6b-0i"/><circle class="qfli1ybnl"/><path class="l1hllojil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myleaf" /></template>
<style>
.bs7nw-m1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.154 18.903a5 5 0 0 0 2.655-.428a10.4 10.4 0 0 0 4.721-2.99c2.203-2.599 2.499-6.328 1.818-7.363c-.651-.99-3.065-.496-4.508-.076a12.54 12.54 0 0 0-5.35 3.515m-4.63 19.964a4.072 4.072 0 0 1 8.144 0Z");
}

.h59g6b-0i {
  cx: 15.111px;
  cy: 40.617px;
  r: 2.883px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1hllojil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.993 40.617h11.878m5.765 0h6.346a9.5 9.5 0 0 0-8.342-9.429l-.208-.07a9.5 9.5 0 0 0-8.178-9.408l-.1-.092v-2.715c0-3.72-.002-8.174-2.579-10.857c-2.669-2.779-9.749-4.354-11.128-3.121s-.052 7.85 2.307 10.585a11.36 11.36 0 0 0 8.278 3.393h.679v2.714l-.101.093a9.5 9.5 0 0 0-8.178 9.408l-.072.07a9.5 9.5 0 0 0-8.342 9.43h6.21");
}

.qfli1ybnl {
  cx: 32.754px;
  cy: 40.617px;
  r: 2.883px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
