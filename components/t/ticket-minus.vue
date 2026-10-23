<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntnuzib5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntnuzib5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ticket-minus" /></template>
