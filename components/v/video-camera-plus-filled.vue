<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl016_q2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl016_q2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:video-camera-plus-filled" /></template>
