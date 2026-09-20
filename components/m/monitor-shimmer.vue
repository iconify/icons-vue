<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1c00mb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1c00mb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-shimmer" /></template>
