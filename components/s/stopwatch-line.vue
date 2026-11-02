<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h34n85n7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h34n85n7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-line" /></template>
