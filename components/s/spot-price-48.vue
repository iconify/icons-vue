<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8w4i5ywu.css';
import '../../css/f/fy5v8duia.css';
import '../../css/a/a-8czfekn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8w4i5ywu"/><path class="fy5v8duia"/><path class="a-8czfekn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spot-price-48" /></template>
