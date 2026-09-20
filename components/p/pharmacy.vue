<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5yc1ib6b.css';
import '../../css/h/huno55bpx.css';
import '../../css/c/cuxq-5b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j5yc1ib6b"/><path class="huno55bpx"/><path class="cuxq-5b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:pharmacy" /></template>
