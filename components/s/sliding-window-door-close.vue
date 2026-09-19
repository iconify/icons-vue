<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqu95vijs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu95vijs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sliding-window-door-close" /></template>
