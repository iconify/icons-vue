<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtpy_02bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vtpy_02bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utah-with-capital-star" /></template>
