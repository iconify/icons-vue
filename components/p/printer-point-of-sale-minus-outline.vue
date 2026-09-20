<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhiko34qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhiko34qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-minus-outline" /></template>
