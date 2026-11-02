<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yue4s31ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yue4s31ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rose-fill" /></template>
