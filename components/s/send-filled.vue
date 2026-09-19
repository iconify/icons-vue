<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4tsc3dmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4tsc3dmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:send-filled" /></template>
