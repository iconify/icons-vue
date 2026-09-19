<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_elnbbbe.css';
import '../../css/z/zt9sedkgs.css';
import '../../css/j/ja5wj7yuy.css';
import '../../css/y/y3wr_vr2v.css';
import '../../css/j/j_xfzjnyd.css';
import '../../css/b/b5tmlbjxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGyLK9kcNn" cx="204.9" cy="-244" r="25.72" fx="204.9" fy="-244" gradientTransform="matrix(-.72758 -1.42335 2.41093 -1.2386 853.636 31.827)" gradientUnits="userSpaceOnUse"><stop offset="0" class="a_elnbbbe"/><stop offset="1" class="zt9sedkgs"/></radialGradient></defs><path fill="url(#SVGyLK9kcNn)" transform="translate(2.065 32.748)scale(.9768)" class="ja5wj7yuy"/><g class="y3wr_vr2v"><path class="j_xfzjnyd"/><path class="b5tmlbjxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sdl" /></template>
