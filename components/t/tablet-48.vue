<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzvt794yl.css';
import '../../css/u/ubmyk0c4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yzvt794yl"/><path class="ubmyk0c4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tablet-48" /></template>
