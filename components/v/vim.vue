<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0akgfb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e0akgfb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vim" /></template>
