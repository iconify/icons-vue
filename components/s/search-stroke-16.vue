<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zstbz94ff.css';
import '../../css/e/ep6g36qhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="zstbz94ff"/><path class="ep6g36qhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:search-stroke-16" /></template>
