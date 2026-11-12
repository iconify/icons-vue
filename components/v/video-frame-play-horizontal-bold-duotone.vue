<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="leiavflem"/><path class="q8oiapbts"/><path class="vr3d5ybqe"/><path class="ux3d6ub6t"/><path class="q3t7r0b_b"/><path class="tt756abdd"/><path class="z8nu7bc_h"/><path class="a5jwaoo5t"/><path class="x4n556b4y"/><path class="x1hubbctl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-play-horizontal-bold-duotone" /></template>
<style>
.a5jwaoo5t {
  fill: currentColor;
  d: path("M11.251 6.25H7.75098V2.06836C8.73213 2.01001 9.88481 2.00133 11.251 2V6.25Z");
}

.leiavflem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22C16.714 22 19.0711 22 20.5355 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.q3t7r0b_b {
  fill: currentColor;
  d: path("M21.7793 17.75C21.585 18.9726 21.2201 19.8512 20.5361 20.5352C19.8521 21.2191 18.9736 21.5841 17.751 21.7783V17.75H21.7793Z");
}

.q8oiapbts {
  fill: currentColor;
  d: path("M11.251 22C9.88481 21.9987 8.73214 21.989 7.75098 21.9307V17.75H11.251V22Z");
}

.tt756abdd {
  fill: currentColor;
  d: path("M10.4014 9.58691C10.8017 9.322 11.3385 9.68269 12.4121 10.4043C13.4713 11.1162 14.001 11.4722 14.001 12C14.001 12.5278 13.4713 12.8838 12.4121 13.5957C11.3385 14.3173 10.8017 14.678 10.4014 14.4131C10.001 14.1482 10.001 13.4322 10.001 12C10.001 10.5678 10.001 9.85184 10.4014 9.58691Z");
}

.ux3d6ub6t {
  fill: currentColor;
  d: path("M6.25098 21.7783C5.02831 21.5841 4.14984 21.2191 3.46582 20.5352C2.78183 19.8512 2.41693 18.9726 2.22266 17.75H6.25098V21.7783Z");
}

.vr3d5ybqe {
  fill: currentColor;
  d: path("M16.251 21.9307C15.2698 21.989 14.1171 21.9987 12.751 22V17.75H16.251V21.9307Z");
}

.x1hubbctl {
  fill: currentColor;
  d: path("M17.751 2.22168C18.9735 2.41591 19.8522 2.78008 20.5361 3.46387C21.2202 4.1479 21.585 5.02727 21.7793 6.25H17.751V2.22168Z");
}

.x4n556b4y {
  fill: currentColor;
  d: path("M12.751 2C14.1171 2.00133 15.2698 2.01001 16.251 2.06836V6.25H12.751V2Z");
}

.z8nu7bc_h {
  fill: currentColor;
  d: path("M6.25098 6.25H2.22266C2.41692 5.02727 2.78179 4.1479 3.46582 3.46387C4.14979 2.78007 5.0285 2.41591 6.25098 2.22168V6.25Z");
}

</style>
