<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m4e9lab1v.css';
import '../../css/j/jilsw3b_d.css';
import '../../css/t/tlyv6rbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m4e9lab1v"/><path class="jilsw3b_d"/><path class="tlyv6rbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-camera-music" /></template>
