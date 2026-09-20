<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc6mrcy9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc6mrcy9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motion-pause-outline" /></template>
