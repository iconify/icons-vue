<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf3d5-a-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wf3d5-a-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tbx" /></template>
