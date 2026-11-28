<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9imfpbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9imfpbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:playlist-play" /></template>
