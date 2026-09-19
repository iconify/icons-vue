<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p30l50b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p30l50b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wardrobe-01" /></template>
