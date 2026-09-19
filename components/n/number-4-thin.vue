<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc2hiecsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc2hiecsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-4-thin" /></template>
