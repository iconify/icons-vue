<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2w2brb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2w2brb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-video-solid" /></template>
