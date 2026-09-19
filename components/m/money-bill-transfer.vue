<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0otvhb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y0otvhb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:money-bill-transfer" /></template>
