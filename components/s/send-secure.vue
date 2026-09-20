<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzb-kg7ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzb-kg7ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-secure" /></template>
