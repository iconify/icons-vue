<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht453tb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht453tb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:spray-can" /></template>
