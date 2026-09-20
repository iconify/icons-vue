<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx5-h5-aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dx5-h5-aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:spiral-shape" /></template>
