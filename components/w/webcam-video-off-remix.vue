<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iin6sj8pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iin6sj8pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:webcam-video-off-remix" /></template>
