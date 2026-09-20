<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo8sfe2_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qo8sfe2_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:star-half-left-o" /></template>
