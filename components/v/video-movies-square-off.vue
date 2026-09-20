<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i41kp_bfp.css';
import '../../css/z/z8wncuzib.css';
import '../../css/j/jo99vqg6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i41kp_bfp"/><path class="z8wncuzib"/><path class="jo99vqg6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:video-movies-square-off" /></template>
