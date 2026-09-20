<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l84l-38cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tumblr-logo-thin" /></template>
<style>
.l84l-38cq {
  fill: currentColor;
  d: path("M192 116a4 4 0 0 0 4-4V72a4 4 0 0 0-4-4h-44V24a4 4 0 0 0-4-4h-32a4 4 0 0 0-4 4a44.05 44.05 0 0 1-44 44a4 4 0 0 0-4 4v40a4 4 0 0 0 4 4h28v60a60.07 60.07 0 0 0 60 60h40a4 4 0 0 0 4-4v-48a4 4 0 0 0-4-4h-32a12 12 0 0 1-12-12v-52Zm-32 72h28v40h-36a52.06 52.06 0 0 1-52-52v-64a4 4 0 0 0-4-4H68V75.85A52.09 52.09 0 0 0 115.85 28H140v44a4 4 0 0 0 4 4h44v32h-44a4 4 0 0 0-4 4v56a20 20 0 0 0 20 20");
}

</style>
