<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9wx0ebay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="e9wx0ebay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-down-on-square" /></template>
