<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lytj4i0za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lytj4i0za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:plugin-2-fill" /></template>
