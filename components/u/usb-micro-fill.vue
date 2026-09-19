<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1yn72bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b1yn72bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:usb-micro-fill" /></template>
