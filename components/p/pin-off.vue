<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4bjv1bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4bjv1bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pin-off" /></template>
