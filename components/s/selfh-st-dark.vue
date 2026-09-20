<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnxl3-vmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tnxl3-vmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:selfh-st-dark" /></template>
