<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5jsvcc-v.css';
import '../../css/g/gszf-lm8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5jsvcc-v"/><path class="gszf-lm8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whiteboard-48" /></template>
