<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg9ul7byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9ul7byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mountain-snow-solid" /></template>
