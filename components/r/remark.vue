<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzkajiu6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vzkajiu6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:remark" /></template>
