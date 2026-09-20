<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xogyj2ogj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xogyj2ogj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb" /></template>
