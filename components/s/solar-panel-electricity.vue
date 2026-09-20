<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epubeu-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epubeu-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-panel-electricity" /></template>
