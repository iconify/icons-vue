<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3yz9_bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3yz9_bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monero-dark" /></template>
