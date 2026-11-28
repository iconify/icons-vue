<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evmif1bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="evmif1bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-x-thin" /></template>
