<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6c-fwi1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y6c-fwi1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:scanner-bar-code" /></template>
