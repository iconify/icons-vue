<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5b2vhb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m5b2vhb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-drag-vertical" /></template>
