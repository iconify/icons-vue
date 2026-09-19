<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueo529fdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ueo529fdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:settings-square" /></template>
