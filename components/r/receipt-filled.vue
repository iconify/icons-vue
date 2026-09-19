<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi9t0_byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi9t0_byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:receipt-filled" /></template>
