<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvdcov6gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="nvdcov6gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tab-unselected" /></template>
