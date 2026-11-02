<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4l3p1bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4l3p1bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ruler-line" /></template>
