<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxytyntgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bxytyntgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-grid-2x2" /></template>
