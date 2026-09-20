<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nund8c9im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1536};
const content = `<path class="nund8c9im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-direction-se" /></template>
