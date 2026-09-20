<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dzgli20pz.css';
import '../../css/e/el85fgywn.css';
import '../../css/o/oootjbbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><ellipse class="dzgli20pz"/><ellipse class="el85fgywn"/><path class="oootjbbym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:toilet-roll" /></template>
