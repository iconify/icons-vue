<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf-bn_bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cf-bn_bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:match-regexp-16" /></template>
