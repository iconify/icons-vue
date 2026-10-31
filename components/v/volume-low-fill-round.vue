<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgp5_cbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgp5_cbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-low-fill-round" /></template>
