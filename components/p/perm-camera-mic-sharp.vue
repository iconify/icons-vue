<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_-gqnfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-camera-mic-sharp" /></template>
<style>
.ck_-gqnfj {
  fill: currentColor;
  d: path("M3 20V6h4.573l1.85-2h5.154l1.85 2H21v14h-8.5v-3.408q1.93-.234 3.216-1.64Q17 13.546 17 11.616h-1q0 1.65-1.175 2.825T12 15.615t-2.825-1.174T8 11.615H7q0 1.931 1.285 3.337t3.215 1.64V20zm9-7.154q.508 0 .87-.361q.36-.362.36-.87v-4q0-.507-.36-.869q-.362-.361-.87-.361t-.87.361q-.36.362-.36.87v4q0 .507.36.869q.362.361.87.361");
}

</style>
