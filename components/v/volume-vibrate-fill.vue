<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi2oy9bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2oy9bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-vibrate-fill" /></template>
