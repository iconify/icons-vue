<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npwzcdxdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npwzcdxdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-4-alert" /></template>
