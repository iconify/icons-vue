<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niiqcdbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="niiqcdbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tree" /></template>
