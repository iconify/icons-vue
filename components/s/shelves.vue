<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdeuu4b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shelves" /></template>
<style>
.fdeuu4b9z {
  fill: currentColor;
  d: path("M4 22.096V1.923h1v2.096h14V1.923h1v20.173h-1V20H5v2.096zM5 11h2.616V7.23h4.769V11H19V5.02H5zm0 8h6.616v-3.77h4.769V19H19v-7H5z");
}

</style>
