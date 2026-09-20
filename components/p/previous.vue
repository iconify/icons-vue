<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz37ntb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mz37ntb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:previous" /></template>
