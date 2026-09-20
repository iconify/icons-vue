<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpf1o5bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpf1o5bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-dashboard-variant-outline" /></template>
