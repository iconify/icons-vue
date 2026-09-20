<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn4c03_ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sn4c03_ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ux" /></template>
