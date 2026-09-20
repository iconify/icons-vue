<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dttdt_m9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dttdt_m9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ruler-line" /></template>
