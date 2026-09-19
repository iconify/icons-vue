<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1lcw4b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i1lcw4b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:workflow" /></template>
