<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-wqontpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q-wqontpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:payment-card" /></template>
