<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxj0xs36a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="sxj0xs36a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:star-circle" /></template>
