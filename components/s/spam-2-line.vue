<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct1chmerr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct1chmerr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spam-2-line" /></template>
