<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpd_3ibmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dpd_3ibmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-bag" /></template>
