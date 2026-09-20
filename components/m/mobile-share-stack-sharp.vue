<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkuw__ooq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-share-stack-sharp" /></template>
<style>
.wkuw__ooq {
  fill: currentColor;
  d: path("M4 23V5h2v16h10v2zm4-4V1h12v4.05h1v3.9h-1V19zm3-7h1.5v-1.75h1.65l-.7.7L14.5 12L17 9.5L14.5 7l-1.05 1.05l.7.7H11z");
}

</style>
