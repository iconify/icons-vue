<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlovz5nrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wlovz5nrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-of-david-filled-outline" /></template>
