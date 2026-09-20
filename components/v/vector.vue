<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk8j7_b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tk8j7_b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vector" /></template>
