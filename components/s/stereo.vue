<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1rs2ilz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="am1rs2ilz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:stereo" /></template>
