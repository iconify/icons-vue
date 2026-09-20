<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2a2-kvtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2a2-kvtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-root" /></template>
