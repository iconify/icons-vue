<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynf38iw_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynf38iw_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reset-right-line" /></template>
