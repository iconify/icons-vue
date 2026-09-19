<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcq18_ykm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcq18_ykm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tumour-outline-24px" /></template>
