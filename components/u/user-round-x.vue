<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsi_ej0qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsi_ej0qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-x" /></template>
