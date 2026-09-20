<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b262p1bwm.css';
import '../../css/j/jubl0mbgj.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/bw835zz1c.css';
import '../../css/l/lyurstbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b262p1bwm"/><path class="jubl0mbgj"/><g class="ij2x_72vy"><path class="bw835zz1c"/><path class="lyurstbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:penguin" /></template>
