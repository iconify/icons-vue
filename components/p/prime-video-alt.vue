<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua17pbcnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua17pbcnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prime-video-alt" /></template>
