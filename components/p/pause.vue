<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5o7gfw9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="t5o7gfw9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pause" /></template>
