<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjw_gbcgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjw_gbcgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stopwatch-2-line" /></template>
