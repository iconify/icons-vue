<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub7f00uxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ub7f00uxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:n-1-square" /></template>
