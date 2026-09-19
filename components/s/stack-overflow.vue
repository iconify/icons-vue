<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuf4_ybad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuf4_ybad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:stack-overflow" /></template>
