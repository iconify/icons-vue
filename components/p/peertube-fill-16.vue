<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbhtql8cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbhtql8cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:peertube-fill-16" /></template>
