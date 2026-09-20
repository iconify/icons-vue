<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le7nlthrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le7nlthrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:utensils" /></template>
