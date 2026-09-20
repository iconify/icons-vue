<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u956u2x8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u956u2x8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-1-block" /></template>
