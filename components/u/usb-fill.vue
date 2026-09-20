<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd1p3wbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd1p3wbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:usb-fill" /></template>
