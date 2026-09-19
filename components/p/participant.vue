<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9z1xfbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w9z1xfbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:participant" /></template>
