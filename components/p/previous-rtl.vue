<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs2agm2zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vs2agm2zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:previous-rtl" /></template>
