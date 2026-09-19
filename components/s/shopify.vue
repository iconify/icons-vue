<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bilw1i94r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bilw1i94r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:shopify" /></template>
