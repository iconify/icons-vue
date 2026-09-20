<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvgep_vpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvgep_vpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-download" /></template>
