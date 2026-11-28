<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vat9n5byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vat9n5byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:org-chart" /></template>
