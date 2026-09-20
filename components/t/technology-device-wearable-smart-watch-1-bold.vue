<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1x4_db-s.css';
import '../../css/z/z759kx8fb.css';
import '../../css/j/jtybs9b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1x4_db-s"/><path class="z759kx8fb"/><path class="jtybs9b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:technology-device-wearable-smart-watch-1-bold" /></template>
