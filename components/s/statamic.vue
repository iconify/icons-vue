<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oypxq_y1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oypxq_y1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:statamic" /></template>
