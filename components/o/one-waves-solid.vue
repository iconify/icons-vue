<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vquwoaczf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vquwoaczf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one-waves-solid" /></template>
