<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fparf6bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fparf6bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sort-alphabetical-descending-fill" /></template>
