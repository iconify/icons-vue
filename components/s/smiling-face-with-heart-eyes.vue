<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/v/v6gjeob1i.css';
import '../../css/i/iq3ofnbqi.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/q/qmnpc1bre.css';
import '../../css/y/yxqzg09mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><path class="v6gjeob1i"/><path class="iq3ofnbqi"/><g class="ij2x_72vy"><circle class="qmnpc1bre"/><path class="yxqzg09mt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:smiling-face-with-heart-eyes" /></template>
