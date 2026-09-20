<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6b44bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw6b44bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant-closed-delivered" /></template>
