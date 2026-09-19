<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sli08-0ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sli08-0ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:search-advanced" /></template>
