<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vef-vgb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vef-vgb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:velas" /></template>
