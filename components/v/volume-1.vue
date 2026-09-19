<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wng3pnz_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wng3pnz_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:volume-1" /></template>
