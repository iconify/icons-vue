<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsrljbwz.css';
import '../../css/q/qnv2-7buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="qnv2-7buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-alert-48" /></template>
