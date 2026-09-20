<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rux370ewv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rux370ewv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-line" /></template>
