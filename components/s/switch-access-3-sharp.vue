<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtuxb-2vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access-3-sharp" /></template>
<style>
.xtuxb-2vy {
  fill: currentColor;
  d: path("m10 16l-1.4-1.4l1.575-1.6H2v-2h8.175L8.6 9.4L10 8l4 4zM2 9V5h4v4zm0 10v-4h4v4zm8 3v-3.175L16.825 12L10 5.175V2h12v5.125h1v4.75h-1V22z");
}

</style>
