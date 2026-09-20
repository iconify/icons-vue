<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_--r1bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d_--r1bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rightmost" /></template>
