<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1mu0_w5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="i1mu0_w5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-envelope" /></template>
