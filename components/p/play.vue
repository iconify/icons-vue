<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgqu7mb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xgqu7mb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:play" /></template>
