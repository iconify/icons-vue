<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxcw1zbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxcw1zbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thermometer-snowflake-filled" /></template>
