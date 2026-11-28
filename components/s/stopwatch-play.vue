<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiw4awa1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiw4awa1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stopwatch-play" /></template>
