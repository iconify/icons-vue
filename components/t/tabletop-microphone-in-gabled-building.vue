<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuspmhkze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yuspmhkze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tabletop-microphone-in-gabled-building" /></template>
