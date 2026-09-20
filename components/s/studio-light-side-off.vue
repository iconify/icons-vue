<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oeulc0p6q"/><path clip-rule="evenodd" class="tkv7wxfbr"/><path clip-rule="evenodd" class="fvppd6r0j"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-light-side-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fvppd6r0j {
  fill-rule: evenodd;
  d: path("M10.793 5.959a1 1 0 0 1 0-1.415l3-3a1 1 0 1 1 1.414 1.415l-3 3a1 1 0 0 1-1.414 0m4.414 8a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.415l3 3a1 1 0 0 1 0 1.415");
}

.oeulc0p6q {
  fill-rule: evenodd;
  d: path("M13.89 4.456C15.22 3.57 17 4.523 17 6.12v3.263c0 1.597-1.78 2.55-3.11 1.664l-2.945-1.963l.888-1.332l-.888-1.333zm-1.337 3.296L15 9.383V6.12zm1.361 10.406a1 1 0 0 1-1.32.507L9.5 17.29v.962a1 1 0 1 1-2 0v-.962l-3.094 1.375a1 1 0 1 1-.812-1.827L7.5 15.102v-3.85a1 1 0 0 1 2 0v3.85l3.906 1.736a1 1 0 0 1 .508 1.32");
}

.tkv7wxfbr {
  fill-rule: evenodd;
  d: path("M4.5 5.752a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2zm6 0h-4v4h4z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
