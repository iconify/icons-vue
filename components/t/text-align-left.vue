<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srp64xlvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="srp64xlvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:text-align-left" /></template>
