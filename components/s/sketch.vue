<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_gu4701j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_gu4701j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:sketch" /></template>
