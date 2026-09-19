<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7srt_bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7srt_bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:think" /></template>
