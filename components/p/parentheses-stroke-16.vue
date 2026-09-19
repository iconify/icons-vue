<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsp1_aclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsp1_aclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:parentheses-stroke-16" /></template>
