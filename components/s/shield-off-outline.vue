<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_r9qybay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_r9qybay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shield-off-outline" /></template>
