<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv_pdp-8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv_pdp-8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:orbit-variant" /></template>
