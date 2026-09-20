<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxitu-r0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxitu-r0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:omega-square-filled" /></template>
