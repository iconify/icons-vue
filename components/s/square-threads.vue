<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td1lfabfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="td1lfabfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-threads" /></template>
