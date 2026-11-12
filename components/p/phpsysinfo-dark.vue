<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iivk5q4jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iivk5q4jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpsysinfo-dark" /></template>
