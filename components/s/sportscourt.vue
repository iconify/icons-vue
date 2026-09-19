<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edp_iow0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="edp_iow0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sportscourt" /></template>
