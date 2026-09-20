<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl43-irdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl43-irdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-dollar-filled" /></template>
