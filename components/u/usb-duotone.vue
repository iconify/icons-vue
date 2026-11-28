<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku_yw01gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku_yw01gy primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:usb-duotone" /></template>
