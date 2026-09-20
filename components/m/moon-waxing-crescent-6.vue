<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnfx4bcxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1537};
const content = `<path class="rnfx4bcxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-crescent-6" /></template>
