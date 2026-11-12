<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npbkuw6op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npbkuw6op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpsysinfo-light" /></template>
