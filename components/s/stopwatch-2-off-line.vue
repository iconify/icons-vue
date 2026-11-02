<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5b7xl8wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5b7xl8wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-2-off-line" /></template>
