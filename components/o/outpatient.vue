<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry477xb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ry477xb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:outpatient" /></template>
