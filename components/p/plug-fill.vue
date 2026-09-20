<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap2f_x_-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap2f_x_-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:plug-fill" /></template>
