<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9huf1b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9huf1b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-search-filled" /></template>
