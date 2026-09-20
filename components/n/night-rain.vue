<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk9_o78-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="nk9_o78-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-rain" /></template>
