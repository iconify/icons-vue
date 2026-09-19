<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgq_h0dcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pgq_h0dcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pen-square" /></template>
