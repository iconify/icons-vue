<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htp4p1bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="htp4p1bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-x-mark-20-solid" /></template>
