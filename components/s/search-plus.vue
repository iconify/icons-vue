<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d63flqyki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="d63flqyki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:search-plus" /></template>
