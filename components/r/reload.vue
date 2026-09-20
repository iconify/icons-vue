<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uny9v1q5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uny9v1q5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:reload" /></template>
