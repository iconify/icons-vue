<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaa1ls8_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aaa1ls8_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:webcam-video-flat" /></template>
