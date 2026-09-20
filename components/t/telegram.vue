<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb_1p-bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mb_1p-bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:telegram" /></template>
