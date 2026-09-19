<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruvf4cbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ruvf4cbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sort-descending" /></template>
