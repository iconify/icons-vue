<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcfsvabbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcfsvabbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-off-fill-round" /></template>
