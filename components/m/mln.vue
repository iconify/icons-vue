<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGoaUnTvqF)" class="wjrwssn4v"/><defs><linearGradient id="SVGoaUnTvqF" x1="12" x2="12" y1="6.162" y2="17.838" gradientUnits="userSpaceOnUse"><stop offset=".24" class="kffun23av"/><stop offset=".66" class="k7si54fov"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mln" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k7si54fov {
  stop-color: var(--svg-color--01cbbf, #01cbbf);
}

.kffun23av {
  stop-color: var(--svg-color--6f4aef, #6f4aef);
}

.wjrwssn4v {
  d: path("M13.703 6.162c-.808 0-1.46.671-1.46 1.498V12H9.324V9.086a.973.973 0 1 0-1.946 0V12H4.946v-.973a.972.972 0 1 0-1.946 0V12h1.946v1.571c0 .745.545 1.348 1.216 1.348c.672 0 1.216-.603 1.216-1.348V12h1.946v4.315a1.494 1.494 0 0 0 1.46 1.523c.807 0 1.46-.681 1.46-1.523V12h2.918v3.42c0 .53.438.958.973.958a.966.966 0 0 0 .973-.958V12h1.946v.973a.973.973 0 1 0 1.946 0V12h-1.946V8.945c0-.462-.438-.837-.973-.837s-.973.375-.973.837V12h-1.946V7.66c0-.827-.652-1.498-1.46-1.498");
}

</style>
