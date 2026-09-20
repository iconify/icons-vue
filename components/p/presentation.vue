<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm--x3eex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bm--x3eex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:presentation" /></template>
