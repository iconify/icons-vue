<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ev7wbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w5ev7wbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark-20-solid" /></template>
