<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csi_j9bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="csi_j9bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:wind-turbine" /></template>
