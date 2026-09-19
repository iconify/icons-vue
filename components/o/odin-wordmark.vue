<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyndy7sli.css';
import '../../css/g/g3se3xb-w.css';
import '../../css/x/xt5fgtbcs.css';
import '../../css/a/a79402b8l.css';
import '../../css/m/myy8ftbvk.css';
import '../../css/d/dmjlzl0xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path fill="url(#SVGtcLqQd5r)" transform="matrix(.03649 0 0 .02684 0 30.72)" class="wyndy7sli"/><path class="g3se3xb-w"/><defs><radialGradient id="SVGtcLqQd5r" cx="0" cy="0" r="1" gradientTransform="scale(3507.87 2480.31)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xt5fgtbcs"/><stop offset=".58" class="a79402b8l"/><stop offset=".8" class="myy8ftbvk"/><stop offset="1" class="dmjlzl0xu"/></radialGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:odin-wordmark" /></template>
