<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx7mcrbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="kx7mcrbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:swap" /></template>
