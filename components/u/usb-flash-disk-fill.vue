<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onvxh595y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onvxh595y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usb-flash-disk-fill" /></template>
