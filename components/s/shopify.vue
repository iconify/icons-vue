<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn0sidbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn0sidbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:shopify" /></template>
