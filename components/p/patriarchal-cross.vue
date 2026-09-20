<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0l-2y22w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m0l-2y22w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:patriarchal-cross" /></template>
