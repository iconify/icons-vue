<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5468drzx.css';
import '../../css/z/zg9s_i7qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e5468drzx"/><path clip-rule="evenodd" class="zg9s_i7qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-store" /></template>
