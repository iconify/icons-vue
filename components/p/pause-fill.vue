<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nczw8dlgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nczw8dlgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pause-fill" /></template>
