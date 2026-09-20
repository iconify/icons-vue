<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztd7czx4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztd7czx4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:report-donut" /></template>
