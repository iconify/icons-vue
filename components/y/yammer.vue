<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0e8keb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h0e8keb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:yammer" /></template>
