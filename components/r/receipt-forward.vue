<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2u2_tbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x2u2_tbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:receipt-forward" /></template>
