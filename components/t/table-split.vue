<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohn3xybzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ohn3xybzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table-split" /></template>
