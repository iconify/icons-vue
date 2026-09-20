<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk7c11bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk7c11bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vibrate-off" /></template>
