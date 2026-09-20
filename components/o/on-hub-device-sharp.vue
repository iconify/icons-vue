<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3uu33gcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:on-hub-device-sharp" /></template>
<style>
.n3uu33gcr {
  fill: currentColor;
  d: path("M8.923 19.77v-1h6.154v1zm0-2.77L7.902 4h8.196l-1.021 13z");
}

</style>
