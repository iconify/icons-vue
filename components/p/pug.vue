<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuw7_9_1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vuw7_9_1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:pug" /></template>
