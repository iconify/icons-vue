<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmoi-m3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcmoi-m3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-square-dashed" /></template>
