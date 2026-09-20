<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlfz_h9nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlfz_h9nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pi" /></template>
