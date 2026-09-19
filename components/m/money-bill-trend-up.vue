<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vny3_-bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vny3_-bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:money-bill-trend-up" /></template>
