<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-bfccc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-bfccc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trend-upward" /></template>
