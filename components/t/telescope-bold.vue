<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0iwjtb9z.css';
import '../../css/w/wvdj1rwub.css';
import '../../css/n/nahr265oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0iwjtb9z"/><path class="wvdj1rwub"/><path class="nahr265oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:telescope-bold" /></template>
