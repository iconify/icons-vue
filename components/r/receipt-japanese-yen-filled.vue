<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_2dczbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_2dczbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-japanese-yen-filled" /></template>
