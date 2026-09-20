<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpce_eve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-paste-outline-sharp" /></template>
<style>
.zvpce_eve {
  fill: currentColor;
  d: path("M12.846 20v-7.5H21V20h-1v-6.5h-2.577V18h-1v-4.5h-2.577V20zM4 20V4h6.252q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20v6.116h-1V5h-3v2.23H8V5H5v14h5.462v1zm8.578-15.003q.23-.233.23-.577t-.233-.575t-.578-.23t-.575.233t-.23.578t.234.575t.577.23t.575-.234");
}

</style>
