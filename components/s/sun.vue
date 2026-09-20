<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypt_fdc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ypt_fdc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sun" /></template>
