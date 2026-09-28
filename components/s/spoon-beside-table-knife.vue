<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le02kybtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="le02kybtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-beside-table-knife" /></template>
