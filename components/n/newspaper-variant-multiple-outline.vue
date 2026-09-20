<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gepoi3bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gepoi3bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper-variant-multiple-outline" /></template>
