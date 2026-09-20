<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvxj2_1-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cvxj2_1-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:piano" /></template>
