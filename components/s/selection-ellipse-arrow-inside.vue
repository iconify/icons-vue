<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy4tthbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy4tthbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-ellipse-arrow-inside" /></template>
