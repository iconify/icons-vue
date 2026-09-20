<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5q0xwacj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5q0xwacj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phoscon-light" /></template>
