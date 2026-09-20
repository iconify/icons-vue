<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-f-pn66e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-f-pn66e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper-plus" /></template>
