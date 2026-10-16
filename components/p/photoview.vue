<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckefjsbym.css';
import '../../css/c/cgs-q85ux.css';
import '../../css/f/fdlh4zbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":768};
const content = `<defs><radialGradient id="SVGD9PZcbhq" cx="0" cy="0" r="1" gradientTransform="matrix(256 -148.196 247.303 427.2 2496 2332.2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ckefjsbym"/><stop offset="1" class="cgs-q85ux"/></radialGradient></defs><path fill="url(#SVGD9PZcbhq)" transform="matrix(1.5 0 0 1.5 -3264 -2826.29)" class="fdlh4zbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:photoview" /></template>
