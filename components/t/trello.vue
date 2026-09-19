<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_gp7lgqe.css';
import '../../css/s/sav6x4bmf.css';
import '../../css/r/rv2a3dbev.css';
import '../../css/z/zn5a8lbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGIbGPWdSe" x1="128" x2="128" y1="0" y2="256" gradientTransform="scale(.5)" gradientUnits="userSpaceOnUse"><stop offset="0" class="g_gp7lgqe"/><stop offset="1" class="sav6x4bmf"/></linearGradient></defs><path fill="url(#SVGIbGPWdSe)" class="rv2a3dbev"/><path class="zn5a8lbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:trello" /></template>
