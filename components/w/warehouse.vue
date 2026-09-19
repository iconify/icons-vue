<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avi9u4biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avi9u4biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:warehouse" /></template>
