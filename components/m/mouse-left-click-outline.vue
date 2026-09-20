<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2aouwtou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2aouwtou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-left-click-outline" /></template>
