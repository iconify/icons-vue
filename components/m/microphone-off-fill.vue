<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-bb-ol-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-bb-ol-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:microphone-off-fill" /></template>
