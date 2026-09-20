<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpeag11mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpeag11mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-2-line" /></template>
