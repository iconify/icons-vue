<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5comzb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o5comzb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:receipt-refund-20-solid" /></template>
