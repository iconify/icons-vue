<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prbei6b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-dock-sharp" /></template>
<style>
.prbei6b4s {
  fill: currentColor;
  d: path("M8.5 21.52v-1h7v1zm4.088-15.434q.22-.222.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.22M6.808 18V2h10.384v3.723h.731v2.9h-.73V18z");
}

</style>
