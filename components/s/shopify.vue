<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnq4f9bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnq4f9bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopify" /></template>
