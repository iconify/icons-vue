<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohll3yb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="ohll3yb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-agenda" /></template>
