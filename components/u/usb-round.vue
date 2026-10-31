<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlro9p6ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlro9p6ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-round" /></template>
