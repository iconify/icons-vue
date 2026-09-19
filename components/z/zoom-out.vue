<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmc6usb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kmc6usb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:zoom-out" /></template>
