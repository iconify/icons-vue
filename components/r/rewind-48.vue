<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4n60ybfu.css';
import '../../css/e/e52uakbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4n60ybfu"/><path class="e52uakbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rewind-48" /></template>
