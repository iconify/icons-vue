<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixase-blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixase-blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:queue-music-outline" /></template>
