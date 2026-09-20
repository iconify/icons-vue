<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyxrm22kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyxrm22kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-off-bold" /></template>
