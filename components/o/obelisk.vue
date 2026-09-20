<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk-_uab5y.css';
import '../../css/q/qg31fgbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xk-_uab5y"/><circle class="qg31fgbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:obelisk" /></template>
