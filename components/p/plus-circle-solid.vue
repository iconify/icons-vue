<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxqzcjb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxqzcjb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plus-circle-solid" /></template>
