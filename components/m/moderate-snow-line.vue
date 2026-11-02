<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jknwwm1_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jknwwm1_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moderate-snow-line" /></template>
