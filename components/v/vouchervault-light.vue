<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3fbqvt5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3fbqvt5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vouchervault-light" /></template>
