<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdm61dbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdm61dbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sanic" /></template>
