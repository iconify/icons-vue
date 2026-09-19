<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0q32_b2b.css';
import '../../css/d/dzv7sjbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m0q32_b2b"/><path class="dzv7sjbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rokit" /></template>
