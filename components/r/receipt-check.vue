<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auxmv3brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auxmv3brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:receipt-check" /></template>
