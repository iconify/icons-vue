<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwd0vej1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pwd0vej1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:webcam-video-remix" /></template>
