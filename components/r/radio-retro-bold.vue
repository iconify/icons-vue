<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjk-yt08k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjk-yt08k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:radio-retro-bold" /></template>
