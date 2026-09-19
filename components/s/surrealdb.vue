<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqch13d3y.css';
import '../../css/h/hke-fq0-t.css';
import '../../css/v/v6eui8b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGZbimedGO" x1="203.348" x2="636.696" y1="-25.413" y2="725.168" gradientTransform="translate(9.137 18.302)scale(.13063)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hqch13d3y"/><stop offset="1" class="hke-fq0-t"/></linearGradient><path fill="url(#SVGZbimedGO)" class="v6eui8b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:surrealdb" /></template>
