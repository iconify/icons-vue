<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uly40t6jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uly40t6jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-2-off-fill" /></template>
