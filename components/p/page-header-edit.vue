<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbwh1_1wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lbwh1_1wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:page-header-edit" /></template>
