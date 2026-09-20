<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usb8k9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="usb8k9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:music" /></template>
