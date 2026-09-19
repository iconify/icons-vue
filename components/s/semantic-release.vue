<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3wqkzi9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3wqkzi9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:semantic-release" /></template>
