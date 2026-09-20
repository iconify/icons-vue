<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx_8hephl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_8hephl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-right" /></template>
