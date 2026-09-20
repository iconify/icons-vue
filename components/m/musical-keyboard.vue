<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzklix2ac.css';
import '../../css/e/ely8642xy.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/x/x38xcickk.css';
import '../../css/o/ob77ulb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uzklix2ac"/><path class="ely8642xy"/><g class="ij2x_72vy"><path class="x38xcickk"/><path class="ob77ulb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:musical-keyboard" /></template>
