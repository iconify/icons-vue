<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8kq6umwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v8kq6umwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:visual-studio" /></template>
