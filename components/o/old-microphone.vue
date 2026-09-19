<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv3vtfbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mv3vtfbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:old-microphone" /></template>
