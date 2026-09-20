<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4xmtobnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4xmtobnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-mower" /></template>
