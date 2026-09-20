<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taul8bcbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taul8bcbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:move-resize" /></template>
