<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyl1ebdmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyl1ebdmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shudder" /></template>
