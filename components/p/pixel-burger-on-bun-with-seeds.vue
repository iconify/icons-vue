<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/walr4d8bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="walr4d8bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-burger-on-bun-with-seeds" /></template>
