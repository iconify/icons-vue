<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8hp-10jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d8hp-10jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-columns" /></template>
