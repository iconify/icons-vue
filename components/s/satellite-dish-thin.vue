<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyxml4bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kyxml4bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:satellite-dish-thin" /></template>
