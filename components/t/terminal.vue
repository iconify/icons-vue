<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4yqj4bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4yqj4bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:terminal" /></template>
