<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bar0usbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bar0usbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:speaker-solid" /></template>
