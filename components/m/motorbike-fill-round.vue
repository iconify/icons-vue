<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n31ha_blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n31ha_blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motorbike-fill-round" /></template>
