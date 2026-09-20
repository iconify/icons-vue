<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkszstbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkszstbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-music-outline" /></template>
