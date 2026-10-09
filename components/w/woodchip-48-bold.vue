<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjbp8ccmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjbp8ccmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:woodchip-48-bold" /></template>
