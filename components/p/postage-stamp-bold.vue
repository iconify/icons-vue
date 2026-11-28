<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ihe_5ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k5ihe_5ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postage-stamp-bold" /></template>
