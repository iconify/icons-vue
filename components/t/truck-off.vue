<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ujv6n5bmi.css';
import '../../css/l/lauwqs8mt.css';
import '../../css/l/l5q_j8fuy.css';
import '../../css/v/vx6mszb2a.css';
import '../../css/w/wp57mfoga.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ujv6n5bmi"/><path clip-rule="evenodd" class="lauwqs8mt"/><path class="l5q_j8fuy"/><path clip-rule="evenodd" class="vx6mszb2a"/><path clip-rule="evenodd" class="wp57mfoga"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:truck-off" /></template>
