<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d81nw-bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d81nw-bwp wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:usb-gloss" /></template>
