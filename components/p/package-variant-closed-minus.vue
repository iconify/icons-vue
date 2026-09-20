<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uymz8obqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uymz8obqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant-closed-minus" /></template>
