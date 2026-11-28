<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck4cn5b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck4cn5b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stopwatch-pause" /></template>
