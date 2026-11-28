<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn5jb6bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nn5jb6bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-x-bold" /></template>
