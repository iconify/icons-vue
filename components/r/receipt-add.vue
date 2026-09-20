<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm_fa0dyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_fa0dyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:receipt-add" /></template>
