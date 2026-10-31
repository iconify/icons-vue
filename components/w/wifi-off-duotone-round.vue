<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2cw-qbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2cw-qbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-off-duotone-round" /></template>
