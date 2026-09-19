<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qddov17ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qddov17ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:right-panel-close-filled" /></template>
