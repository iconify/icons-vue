<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6thek59e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6thek59e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:music-filled" /></template>
