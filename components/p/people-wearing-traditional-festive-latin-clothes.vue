<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mioqd3brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mioqd3brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-wearing-traditional-festive-latin-clothes" /></template>
