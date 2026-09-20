<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-uuo95uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shower-sharp" /></template>
<style>
.y-uuo95uv {
  fill: currentColor;
  d: path("M8.076 16.923q-.328 0-.548-.221q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.222.547t-.549.22m3.924 0q-.328 0-.548-.221t-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22m3.924 0q-.328 0-.548-.221t-.22-.55t.222-.547q.221-.22.549-.22t.547.221t.22.55t-.221.547t-.55.22M6 13v-1q0-2.361 1.594-4.071T11.5 6.023V4h1v2.023q2.312.196 3.906 1.906T18 12v1zm2.076 6.846q-.328 0-.548-.221q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.222.547t-.549.22m3.924 0q-.328 0-.548-.221q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22m3.924 0q-.328 0-.548-.221q-.22-.222-.22-.55t.222-.547t.549-.22t.547.221t.22.55t-.221.547t-.55.22");
}

</style>
