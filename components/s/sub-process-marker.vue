<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwub5-btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="iwub5-btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:sub-process-marker" /></template>
