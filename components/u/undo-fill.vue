<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slsv3cbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slsv3cbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:undo-fill" /></template>
