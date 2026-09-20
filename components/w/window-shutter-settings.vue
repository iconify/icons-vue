<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg47drjgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg47drjgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-shutter-settings" /></template>
