<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m89f5kbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m89f5kbev primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-duotone" /></template>
