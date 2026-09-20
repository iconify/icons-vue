<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wloq5pbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wloq5pbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-negative-1" /></template>
