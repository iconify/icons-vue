<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2i0ippj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2i0ippj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:set-top-box" /></template>
