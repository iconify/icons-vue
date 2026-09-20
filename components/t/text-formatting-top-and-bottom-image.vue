<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2_3kdbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n2_3kdbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-top-and-bottom-image" /></template>
