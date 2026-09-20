<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq_gakbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zq_gakbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tab-a" /></template>
