<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxz5dc_of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxz5dc_of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:signoz-dark" /></template>
