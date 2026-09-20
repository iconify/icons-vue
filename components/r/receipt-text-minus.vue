<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpc5t2beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpc5t2beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-minus" /></template>
