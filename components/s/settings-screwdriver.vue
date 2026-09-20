<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/figruzihz.css';
import '../../css/l/ll5ze5bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="figruzihz"/><path class="ll5ze5bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:settings-screwdriver" /></template>
