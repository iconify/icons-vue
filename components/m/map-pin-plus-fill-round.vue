<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfyvin1tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfyvin1tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-plus-fill-round" /></template>
