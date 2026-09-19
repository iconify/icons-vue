<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_2xnfb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h_2xnfb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:xbox" /></template>
