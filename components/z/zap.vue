<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db3bihb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="db3bihb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:zap" /></template>
