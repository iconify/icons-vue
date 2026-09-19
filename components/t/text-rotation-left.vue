<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpq-7-bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wpq-7-bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-rotation-left" /></template>
