<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3jil3bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3jil3bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vercel-ignore" /></template>
