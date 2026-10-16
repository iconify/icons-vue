<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx_rtncis.css';
import '../../css/e/e0nmxkmog.css';
import '../../css/y/ygtv74bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mx_rtncis"/><path class="e0nmxkmog"/><path class="ygtv74bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-alert-48-bold" /></template>
