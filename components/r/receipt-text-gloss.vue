<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1af6gbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1af6gbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:receipt-text-gloss" /></template>
