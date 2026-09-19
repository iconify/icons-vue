<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfneizbci.css';
import '../../css/g/g81nz19ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vfneizbci"/><path class="g81nz19ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:paypal" /></template>
