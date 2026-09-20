<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnjfysbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mnjfysbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stencilbox-light" /></template>
