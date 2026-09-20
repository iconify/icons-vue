<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mslv4ubvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mslv4ubvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scarf-line" /></template>
