<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltxah4b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ltxah4b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-interface" /></template>
