<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfai6u5du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mfai6u5du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:start-event-timer" /></template>
