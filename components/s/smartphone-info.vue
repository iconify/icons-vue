<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqzy0acgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":480};
const content = `<path class="mqzy0acgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-info" /></template>
