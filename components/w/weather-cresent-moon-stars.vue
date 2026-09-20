<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzn1vy6ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rzn1vy6ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-cresent-moon-stars" /></template>
