<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbv695bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbv695bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:microphone-off" /></template>
