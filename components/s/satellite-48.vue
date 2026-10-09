<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le28xpbbv.css';
import '../../css/o/o8rtphxyj.css';
import '../../css/c/czocnxqcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="le28xpbbv"/><path class="o8rtphxyj"/><path class="czocnxqcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-48" /></template>
