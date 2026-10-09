<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_7szbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zr_7szbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tornado-48" /></template>
