<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky022pehc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky022pehc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:select-circle-area-2-flat" /></template>
