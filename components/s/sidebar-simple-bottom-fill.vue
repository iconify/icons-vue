<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usbif_0ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="usbif_0ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-bottom-fill" /></template>
