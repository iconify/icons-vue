<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_rfb9hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_rfb9hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-alert" /></template>
