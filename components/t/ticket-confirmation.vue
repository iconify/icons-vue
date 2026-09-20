<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmpz7gb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmpz7gb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ticket-confirmation" /></template>
