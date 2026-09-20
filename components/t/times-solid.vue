<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf63asb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf63asb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:times-solid" /></template>
