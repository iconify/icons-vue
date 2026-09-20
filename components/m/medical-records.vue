<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3avu39bx.css';
import '../../css/m/mgwh73i-d.css';
import '../../css/h/hyk4wfaif.css';
import '../../css/e/ehn65vx3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j3avu39bx"/><path class="mgwh73i-d"/><path class="hyk4wfaif"/><path class="ehn65vx3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:medical-records" /></template>
