<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ppw9blh.css';
import '../../css/s/sqkxxvbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="s9ppw9blh"/><path class="sqkxxvbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-online" /></template>
