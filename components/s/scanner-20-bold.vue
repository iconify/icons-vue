<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9fpfpb1i.css';
import '../../css/d/diwo_7x5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y9fpfpb1i"/><path class="diwo_7x5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scanner-20-bold" /></template>
