<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhhnl_bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hhhnl_bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:text-align-center" /></template>
