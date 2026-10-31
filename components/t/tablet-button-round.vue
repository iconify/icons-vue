<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qua3fz37b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qua3fz37b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-button-round" /></template>
