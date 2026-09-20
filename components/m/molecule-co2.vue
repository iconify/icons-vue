<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o87_bv_-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o87_bv_-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:molecule-co2" /></template>
