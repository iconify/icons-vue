<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy6hdmbvr.css';
import '../../css/q/qfu31qb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6hdmbvr"/><path class="qfu31qb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-3-line" /></template>
