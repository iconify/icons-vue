<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVNLNIeuJ)" clip-rule="evenodd" class="haxbx6b8n"/><path fill="url(#SVGR4FbJbOW)" class="e8w31-z2z"/><path class="tjoxwbcbl"/><path class="b_jj5xb1p"/><defs><linearGradient id="SVGVNLNIeuJ" x1="3.559" x2="20.028" y1="12.469" y2="9.908" gradientUnits="userSpaceOnUse"><stop class="jdatt4bkt"/><stop offset=".24" class="gek0jac1j"/><stop offset=".46" class="s89eigx1i"/><stop offset=".75" class="f72l5noye"/><stop offset="1" class="jafcovb0t"/></linearGradient><linearGradient id="SVGR4FbJbOW" x1="16.462" x2="20.224" y1="14.845" y2="17.708" gradientUnits="userSpaceOnUse"><stop class="fot1rkbwv"/><stop offset="1" class="t44vszbce"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vcore" /></template>
<style>
.b_jj5xb1p {
  fill: var(--svg-color--b38b3e, #b38b3e);
  d: path("M5.682 5.6c.741.328 1.71.582 2.434.216l.63-.322c.704-.37.868-.46 1.466-.318c.28.069.508.249.741.429c.381.301.778.614 1.46.46c.985-.222 2.71-1.35 2.71-2.503a8.98 8.98 0 0 0-9.44 2.032z");
}

.e8w31-z2z {
  d: path("M20.505 14.94a9 9 0 0 1-2.863 4.075c-.9-.889-1.73-2.963-.71-4.128c.99-1.127 2.7-.486 3.573.053");
}

.f72l5noye {
  stop-color: var(--svg-color--fbd072, #fbd072);
}

.fot1rkbwv {
  stop-color: var(--svg-color--bc8e3a, #bc8e3a);
}

.ft5dv1b6b {
  fill: none;
}

.gek0jac1j {
  stop-color: var(--svg-color--cea651, #cea651);
}

.haxbx6b8n {
  fill-rule: evenodd;
  d: path("M20.997 12.004a8.996 8.996 0 1 1-17.993 0a8.996 8.996 0 0 1 17.993 0m-7.97-5.292h2.118l-1.493 3.704l4.7-1.497v2.021l-3.335 1.064l3.334 1.058v2.027l-4.593-1.471l1.482 3.678h-2.117L12 14.518l-1.122 2.778H8.762l1.524-3.779L5.651 15v-2.022l3.053-.979l-3.053-.973V9.003l4.741 1.519l-1.534-3.81h2.116l1.027 2.545z");
}

.jafcovb0t {
  stop-color: var(--svg-color--fcc766, #fcc766);
}

.jdatt4bkt {
  stop-color: var(--svg-color--d3a955, #d3a955);
}

.s89eigx1i {
  stop-color: var(--svg-color--ffd57e, #ffd57e);
}

.t44vszbce {
  stop-color: var(--svg-color--79622d, #79622d);
}

.tjoxwbcbl {
  fill: var(--svg-color--c49d41, #c49d41);
  d: path("M8.281 20.195a9.03 9.03 0 0 1-4.403-4.318c.71-.265 1.895-.34 3.064.714c1.313 1.185 1.524 2.757 1.34 3.604");
}

</style>
