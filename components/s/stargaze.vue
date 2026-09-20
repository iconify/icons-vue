<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f77g8-b6h"/><path fill="url(#SVGOZGuGezA)" class="jx0n_29_m"/><path class="da1uzgwwj"/><path fill="url(#SVGeGxjzagl)" class="p94ec7bby"/><defs><linearGradient id="SVGOZGuGezA" x1="-3.298" x2="27.1" y1="1.488" y2="1.488" gradientUnits="userSpaceOnUse"><stop offset=".49" class="ywp3nmzlb"/><stop offset=".5" class="sug9cdb5w"/></linearGradient><linearGradient id="SVGeGxjzagl" x1="3.002" x2="21" y1="10.901" y2="10.901" gradientUnits="userSpaceOnUse"><stop offset=".49" class="ywp3nmzlb"/><stop offset=".5" class="sug9cdb5w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stargaze" /></template>
<style>
.da1uzgwwj {
  fill: var(--svg-color--dba527, #dba527);
  d: path("M16.839 14.337a.266.266 0 0 0 .444.106l3.637-3.637a.271.271 0 0 0-.154-.46l-5.028-.704a.27.27 0 0 0-.297.349z");
}

.f77g8-b6h {
  fill: var(--svg-color--e2bb5e, #e2bb5e);
  d: path("M8.58 9.986a.27.27 0 0 0-.29-.355l-5.055.72a.27.27 0 0 0-.229.325a.27.27 0 0 0 .07.13l3.6 3.716a.266.266 0 0 0 .377.013a.3.3 0 0 0 .072-.119z");
}

.ft5dv1b6b {
  fill: none;
}

.jx0n_29_m {
  d: path("M6.744 20.392a.265.265 0 0 0 .376.318l4.727-2.245a.27.27 0 0 1 .222 0l4.939 2.24a.27.27 0 0 0 .365-.334c-.931-2.805-1.773-5.579-2.673-8.38a.265.265 0 0 0-.476-.052l-1.996 3.578a.27.27 0 0 1-.238.138h-.085a.26.26 0 0 1-.233-.143L9.735 11.95a.26.26 0 0 0-.233-.143h-.026a.266.266 0 0 0-.26.19a244 244 0 0 0-2.472 8.395");
}

.p94ec7bby {
  d: path("M14.023 9.552a.32.32 0 0 0 0-.25l-.027-.063l-1.784-5.78a.265.265 0 0 0-.513 0l-1.747 5.78l-.026.085a.3.3 0 0 0 .01.201l1.731 3.991a.28.28 0 0 0 .244.16h.063a.27.27 0 0 0 .244-.16l1.8-3.964z");
}

.sug9cdb5w {
  stop-color: var(--svg-color--dba527, #dba527);
}

.ywp3nmzlb {
  stop-color: var(--svg-color--e2bb5e, #e2bb5e);
}

</style>
