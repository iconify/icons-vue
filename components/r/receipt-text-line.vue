<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec0nt3i4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec0nt3i4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:receipt-text-line" /></template>
