<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfuom7_gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfuom7_gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:texture" /></template>
