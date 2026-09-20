<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxpxfkt8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxpxfkt8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-leaf" /></template>
