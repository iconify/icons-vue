<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7-w1bcfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t7-w1bcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:torii-gate-solid" /></template>
