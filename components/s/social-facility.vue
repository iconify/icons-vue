<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usb26tbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="usb26tbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:social-facility" /></template>
