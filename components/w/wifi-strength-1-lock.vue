<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2yti383j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2yti383j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-1-lock" /></template>
