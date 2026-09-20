<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx7n_hboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx7n_hboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radiobox-marked" /></template>
