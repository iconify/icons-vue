<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb-f-i0ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb-f-i0ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stairs-fill" /></template>
