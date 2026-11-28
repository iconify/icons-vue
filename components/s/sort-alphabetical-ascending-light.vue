<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuf1bstzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uuf1bstzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sort-alphabetical-ascending-light" /></template>
