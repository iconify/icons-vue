<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy_govjhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hy_govjhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:page-break-light" /></template>
