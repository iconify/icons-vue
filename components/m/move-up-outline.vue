<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnbjlzbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-up-outline" /></template>
<style>
.jnbjlzbzl {
  fill: currentColor;
  d: path("M8.442 19q-2.56 0-4.385-1.73T2.23 13t1.926-4.21t4.557-1.798L6.658 4.92l.707-.707l3.29 3.287l-3.288 3.289l-.708-.714l2.07-2.071q-2.216.119-3.857 1.504q-1.64 1.384-1.64 3.492q0 2.114 1.54 3.557Q6.31 18 8.46 18h2.04v1zm5.058-8.192V5H21v5.808zm0 8.192v-5.808H21V19zm1-1H20v-3.808h-5.5z");
}

</style>
