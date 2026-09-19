<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkr_h4dal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkr_h4dal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:save" /></template>
