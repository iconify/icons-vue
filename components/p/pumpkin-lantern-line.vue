<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc2_9ibwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc2_9ibwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pumpkin-lantern-line" /></template>
