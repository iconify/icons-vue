<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l49z6bbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l49z6bbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tray-remove" /></template>
