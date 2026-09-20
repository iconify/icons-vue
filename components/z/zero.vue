<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnl_rbnua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnl_rbnua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:zero" /></template>
