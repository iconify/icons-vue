<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_0kicbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_0kicbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-4-fill" /></template>
