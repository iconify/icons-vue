<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5jyccdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw5jyccdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:refund-line" /></template>
