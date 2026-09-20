<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ykdnb4c.css';
import '../../css/b/bv8dp7-9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7ykdnb4c"/><path class="bv8dp7-9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-1" /></template>
