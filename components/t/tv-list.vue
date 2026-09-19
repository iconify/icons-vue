<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltv1hrb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ltv1hrb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tv-list" /></template>
