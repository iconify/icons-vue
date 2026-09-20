<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba_6bfbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ba_6bfbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pricebuddy" /></template>
