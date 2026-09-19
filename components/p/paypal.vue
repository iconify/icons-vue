<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud8u_abuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ud8u_abuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:paypal" /></template>
