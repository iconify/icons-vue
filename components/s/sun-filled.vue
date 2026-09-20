<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klc5_r1ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klc5_r1ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sun-filled" /></template>
