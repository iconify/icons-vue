<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jadl1ismj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jadl1ismj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:old-time-camera" /></template>
