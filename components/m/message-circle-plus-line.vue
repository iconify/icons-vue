<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roib-2ula.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roib-2ula"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-plus-line" /></template>
