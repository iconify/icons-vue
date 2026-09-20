<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6f0eobmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:service-toolbox-sharp" /></template>
<style>
.p6f0eobmt {
  fill: currentColor;
  d: path("M3 19v-5.308h4.5v1h1v-1h7v1h1v-1H21V19zm.175-6.308L5.679 7h2.513V5.846q0-.402.3-.7q.299-.3.7-.3h5.616q.402 0 .7.3q.3.298.3.7V7h2.513l2.504 5.692H16.5v-1h-1v1h-7v-1h-1v1zM9.192 7h5.616V5.846H9.192z");
}

</style>
