<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssld43bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ssld43bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:star-half-right" /></template>
