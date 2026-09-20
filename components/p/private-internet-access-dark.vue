<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw86oacsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw86oacsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:private-internet-access-dark" /></template>
