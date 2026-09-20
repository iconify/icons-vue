<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou6xlkbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou6xlkbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-line" /></template>
