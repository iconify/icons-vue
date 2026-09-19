<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz01vrbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":448};
const content = `<path class="oz01vrbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:up" /></template>
