<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt7murb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt7murb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:videocam-outline" /></template>
