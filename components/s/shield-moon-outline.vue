<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asi4edbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asi4edbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-moon-outline" /></template>
