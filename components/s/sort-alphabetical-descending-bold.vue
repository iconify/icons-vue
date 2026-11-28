<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0w-96bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y0w-96bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sort-alphabetical-descending-bold" /></template>
