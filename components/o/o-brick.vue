<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r87fz2wei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r87fz2wei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:o-brick" /></template>
