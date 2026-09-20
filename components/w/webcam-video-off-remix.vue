<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsf4d8bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rsf4d8bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-video-off-remix" /></template>
