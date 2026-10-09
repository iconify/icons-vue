<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqtu_acra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sqtu_acra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:strikethrough-48" /></template>
