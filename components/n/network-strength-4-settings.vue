<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9bo6tbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9bo6tbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-4-settings" /></template>
