<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxh033eqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vxh033eqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:receipt-percent-20-solid" /></template>
