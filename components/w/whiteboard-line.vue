<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oau11fbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oau11fbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:whiteboard-line" /></template>
