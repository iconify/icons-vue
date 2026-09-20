<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_9mrpio.css';
import '../../css/t/te90vbbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fj_9mrpio"/><path class="te90vbbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-microphone-2" /></template>
