<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2r11p14s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2r11p14s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velld-light" /></template>
