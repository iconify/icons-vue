<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytj0k685m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj0k685m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:receipt-refund" /></template>
