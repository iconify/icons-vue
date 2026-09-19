<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp5m1r47p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zp5m1r47p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:xing-square" /></template>
