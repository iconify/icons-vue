<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue9mixg-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9mixg-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-play-reverse-outline" /></template>
