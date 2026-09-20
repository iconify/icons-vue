<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv4qqnbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv4qqnbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-angle" /></template>
