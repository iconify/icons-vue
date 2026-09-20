<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih43bbble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih43bbble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-play" /></template>
