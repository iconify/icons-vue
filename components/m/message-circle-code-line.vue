<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaav9wpwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaav9wpwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-code-line" /></template>
