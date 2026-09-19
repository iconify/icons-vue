<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agh5kobes.css';
import '../../css/f/fe-l95ejb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agh5kobes"/><path class="fe-l95ejb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:price-tag" /></template>
