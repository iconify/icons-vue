<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6uo6sbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6uo6sbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-2-lock" /></template>
