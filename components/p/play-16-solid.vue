<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy8t4sbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yy8t4sbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:play-16-solid" /></template>
