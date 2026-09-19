<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny1aodbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ny1aodbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nativescript" /></template>
