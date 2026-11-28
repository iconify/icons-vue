<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td_0am-yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="td_0am-yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:table-of-contents" /></template>
