<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxz--3bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxz--3bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:robot-2-line" /></template>
