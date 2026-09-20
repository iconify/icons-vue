<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgws2bbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgws2bbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-camera-off" /></template>
