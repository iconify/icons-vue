<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxl1ejw5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxl1ejw5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:videocam" /></template>
