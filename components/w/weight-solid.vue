<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw78_1bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw78_1bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:weight-solid" /></template>
