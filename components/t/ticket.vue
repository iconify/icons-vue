<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an_vu3bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="an_vu3bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:ticket" /></template>
