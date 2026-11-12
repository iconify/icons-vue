<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsg338bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsg338bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windmill-light" /></template>
