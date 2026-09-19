<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6xu7ib6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c6xu7ib6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:printer-outline" /></template>
