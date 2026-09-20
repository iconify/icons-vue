<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxwfhhekf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soundbar-outline-sharp" /></template>
<style>
.lxwfhhekf {
  fill: currentColor;
  d: path("M11.5 12.577h1V9.692h-1zM5.77 18v-1H9v1zM15 18v-1h3.23v1zm-7.73-5.423q.613 0 1.027-.414q.414-.415.414-1.019t-.414-1.018t-1.018-.414t-1.028.417t-.424 1.005q0 .614.423 1.028q.424.415 1.02.415m9.455.02q.6 0 1.034-.428q.433-.428.433-1.028t-.431-1.025t-1.038-.424t-1.03.424t-.424 1.025t.428 1.028t1.028.427M3 15.27V7h18v8.27zm1-1h16V8H4zm8-3.135");
}

</style>
