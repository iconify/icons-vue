<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed9732byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ed9732byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tshirt" /></template>
