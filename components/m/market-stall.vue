<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1bteab6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w1bteab6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:market-stall" /></template>
