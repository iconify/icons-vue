<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vahm3b6vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vahm3b6vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-2-fill" /></template>
