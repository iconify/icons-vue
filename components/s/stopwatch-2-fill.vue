<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0ci2b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co0ci2b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-2-fill" /></template>
