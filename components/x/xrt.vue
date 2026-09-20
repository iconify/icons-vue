<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="a-0fgl0be"/><path class="cv916frxq"/><path class="merqthbvp"/><path class="xyxketbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xrt" /></template>
<style>
.a-0fgl0be {
  fill: var(--svg-color--03a2e5, #03a2e5);
  fill-rule: evenodd;
  d: path("M12.282 5.174a.56.56 0 1 0-.637-.92a.562.562 0 0 0 .066.932L3.816 18.803a.56.56 0 1 0 .306.5h15.729a.56.56 0 0 0 .562.56a.56.56 0 1 0-.017-1.12zm7.84 13.65L11.986 5.26L4.029 18.993l.017.028h15.881a.56.56 0 0 1 .194-.198");
}

.cv916frxq {
  fill: var(--svg-color--545873, #545873);
  d: path("m8.055 16.496l3.93-2.028l3.934 2.028z");
}

.ft5dv1b6b {
  fill: none;
}

.merqthbvp {
  fill: var(--svg-color--00a8eb, #00a8eb);
  d: path("m11.987 9.753l-3.932 6.74l3.932-1.988z");
}

.xyxketbhc {
  fill: var(--svg-color--b4c0f2, #b4c0f2);
  d: path("m11.987 9.753l3.932 6.74l-3.932-1.988z");
}

</style>
