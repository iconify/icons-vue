<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbkmpjbyx.css';
import '../../css/a/ag9gbdcug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbkmpjbyx"/><path class="ag9gbdcug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-line" /></template>
