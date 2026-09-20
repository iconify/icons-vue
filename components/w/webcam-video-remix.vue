<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtz19omd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lbtz19omd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-video-remix" /></template>
