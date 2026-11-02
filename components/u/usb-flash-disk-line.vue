<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8t01ccwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8t01ccwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usb-flash-disk-line" /></template>
