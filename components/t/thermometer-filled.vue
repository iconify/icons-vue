<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9sybde8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9sybde8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:thermometer-filled" /></template>
