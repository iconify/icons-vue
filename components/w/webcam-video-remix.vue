<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35i7-b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j35i7-b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:webcam-video-remix" /></template>
