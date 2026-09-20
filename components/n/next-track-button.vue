<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2x_72vy.css';
import '../../css/z/z6wmufbrf.css';
import '../../css/j/j0dvfnbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="z6wmufbrf"/><path class="j0dvfnbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:next-track-button" /></template>
