<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj0an3bgo.css';
import '../../css/m/mjrq3v7lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj0an3bgo"/><path class="mjrq3v7lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:music-note-1" /></template>
