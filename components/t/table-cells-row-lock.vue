<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz2cl-9kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tz2cl-9kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:table-cells-row-lock" /></template>
