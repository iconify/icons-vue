<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd8m2mqxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd8m2mqxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:video-camera-solid" /></template>
