<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7_dlbcgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="w7_dlbcgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-rain-wind" /></template>
