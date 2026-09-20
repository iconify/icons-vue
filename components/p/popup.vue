<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxp3iactp.css';
import '../../css/h/hy2z1dbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cxp3iactp"/><path class="hy2z1dbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:popup" /></template>
