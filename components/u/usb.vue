<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm2by1bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2by1bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:usb" /></template>
