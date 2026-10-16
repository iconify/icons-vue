<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctvev1biw.css';
import '../../css/q/qis7irbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ctvev1biw"/><path class="qis7irbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:money-bag-48-bold" /></template>
