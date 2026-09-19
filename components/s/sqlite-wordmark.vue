<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzcvz811g.css';
import '../../css/q/qjsdyqb7c.css';
import '../../css/q/qnq9qcc5n.css';
import '../../css/d/d0vzzrbue.css';
import '../../css/a/a_r35gb4i.css';
import '../../css/y/ye49fbbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGDXs8adzz" x1="-15.615" x2="-6.741" y1="-9.108" y2="-9.108" gradientTransform="matrix(0 4.0868 -4.0632 0 -14.448 103.81)" gradientUnits="userSpaceOnUse"><stop offset="0" class="dzcvz811g"/><stop offset=".92" class="qjsdyqb7c"/><stop offset="1" class="qjsdyqb7c"/></linearGradient></defs><path class="qnq9qcc5n"/><path class="d0vzzrbue"/><path fill="url(#SVGDXs8adzz)" class="a_r35gb4i"/><path class="ye49fbbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sqlite-wordmark" /></template>
