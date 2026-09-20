<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye8wajbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8wajbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skull" /></template>
