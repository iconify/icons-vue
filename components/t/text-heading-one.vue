<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtf68bbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtf68bbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-heading-one" /></template>
