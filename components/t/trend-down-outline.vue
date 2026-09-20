<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl-yckb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zl-yckb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trend-down-outline" /></template>
