<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frv0s0blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frv0s0blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pumpkin" /></template>
