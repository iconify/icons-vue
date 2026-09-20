<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoagr4blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qoagr4blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:rss-alt" /></template>
