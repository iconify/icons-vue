<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh2t6e4ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yh2t6e4ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-subtitles-solid-expressive" /></template>
