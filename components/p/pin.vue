<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajo6xxbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajo6xxbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:pin" /></template>
