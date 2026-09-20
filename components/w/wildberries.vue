<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o51vhd6du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":75.1};
const content = `<path class="o51vhd6du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wildberries" /></template>
