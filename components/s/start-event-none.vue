<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbrnwgbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kbrnwgbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:start-event-none" /></template>
