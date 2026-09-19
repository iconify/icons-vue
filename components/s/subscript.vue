<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o23mqgb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o23mqgb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:subscript" /></template>
