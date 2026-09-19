<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d44248blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d44248blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:stencil" /></template>
