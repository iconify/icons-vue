<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb14r95-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb14r95-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tray-full" /></template>
