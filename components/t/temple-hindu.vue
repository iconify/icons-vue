<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8g_8fjxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:temple-hindu" /></template>
<style>
.l8g_8fjxq {
  fill: currentColor;
  d: path("m8.185 7.5l1.29-4.298V1.5h1v2H13.5v-2h1v1.577L15.816 7.5zM2.5 21.5v-10h1v2h2.866l.307-1h10.654l.308 1H20.5v-2h1v10h-8v-5h-3v5zm4.485-10l.888-3h8.254l.889 3z");
}

</style>
