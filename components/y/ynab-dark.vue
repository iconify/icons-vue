<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd_1g2ahb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd_1g2ahb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ynab-dark" /></template>
