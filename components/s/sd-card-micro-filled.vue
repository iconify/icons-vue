<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0_iybcdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y0_iybcdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sd-card-micro-filled" /></template>
