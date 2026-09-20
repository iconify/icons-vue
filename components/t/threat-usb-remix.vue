<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mind97vlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mind97vlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:threat-usb-remix" /></template>
