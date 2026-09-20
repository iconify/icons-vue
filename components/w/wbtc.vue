<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq8hp2o_x.css';
import '../../css/o/o3ulf3bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq8hp2o_x"/><path class="o3ulf3bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wbtc" /></template>
