<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxf93rbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf93rbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:medicine-capsule-2" /></template>
