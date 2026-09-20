<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szvk_z3ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szvk_z3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-quick-outline" /></template>
