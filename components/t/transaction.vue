<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m28dodbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m28dodbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:transaction" /></template>
