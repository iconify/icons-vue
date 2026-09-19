<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjyy7ib5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xjyy7ib5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:triangle-left" /></template>
