<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ied5ywnfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ied5ywnfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:spiral-shape-flat" /></template>
