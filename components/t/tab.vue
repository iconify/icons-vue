<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgi5-_mrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sgi5-_mrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tab" /></template>
