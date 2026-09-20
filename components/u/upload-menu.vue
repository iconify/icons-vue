<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhoz0_dzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhoz0_dzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:upload-menu" /></template>
