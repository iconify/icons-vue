<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzhd2pbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fzhd2pbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:one-of-bamboos-mahjong-ss02" /></template>
