<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_qnxmbps.css';
import '../../css/n/np6k2ybks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e_qnxmbps"/><path class="np6k2ybks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-bank" /></template>
