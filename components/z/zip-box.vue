<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/secb7r11d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secb7r11d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zip-box" /></template>
