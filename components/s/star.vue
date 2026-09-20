<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlysuybdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="vlysuybdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:star" /></template>
