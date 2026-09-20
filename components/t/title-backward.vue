<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeqly5bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeqly5bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:title-backward" /></template>
