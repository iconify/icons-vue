<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz2ti29gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz2ti29gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-square-bold" /></template>
