<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt2iqb_gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yt2iqb_gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:music-equalizer" /></template>
