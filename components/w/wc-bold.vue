<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jes5hmb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jes5hmb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:wc-bold" /></template>
