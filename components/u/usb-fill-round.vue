<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hck5hdcca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hck5hdcca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-fill-round" /></template>
