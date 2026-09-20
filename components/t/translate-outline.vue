<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k97f4fb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k97f4fb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:translate-outline" /></template>
