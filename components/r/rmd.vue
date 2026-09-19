<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyqguudvt.css';
import '../../css/j/j8kj3rs0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jyqguudvt"/><path class="j8kj3rs0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rmd" /></template>
