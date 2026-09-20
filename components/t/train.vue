<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzo_s6m5m.css';
import '../../css/m/mfabyo3pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hzo_s6m5m"/><path class="mfabyo3pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:train" /></template>
