<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqs_8pbmm.css';
import '../../css/c/c-9yccowm.css';
import '../../css/c/cpqrj-bqc.css';
import '../../css/o/orezepfbe.css';
import '../../css/y/ygtv74bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qqs_8pbmm"/><path class="c-9yccowm"/><path class="cpqrj-bqc"/><path class="orezepfbe"/><path class="ygtv74bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tracker-alert-48-bold" /></template>
