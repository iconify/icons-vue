<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i56jn-xon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i56jn-xon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:roblox" /></template>
