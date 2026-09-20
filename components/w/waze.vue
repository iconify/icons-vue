<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t65crrbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t65crrbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:waze" /></template>
