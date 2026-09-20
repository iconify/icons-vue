<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k072b1bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k072b1bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:order-numeric-ascending" /></template>
