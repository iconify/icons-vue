<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srrlq36sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="srrlq36sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-light" /></template>
