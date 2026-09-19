<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hicvn82qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1824};
const content = `<path class="hicvn82qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:paper-plane-o" /></template>
