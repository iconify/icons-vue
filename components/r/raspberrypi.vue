<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i64w7zb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i64w7zb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:raspberrypi" /></template>
