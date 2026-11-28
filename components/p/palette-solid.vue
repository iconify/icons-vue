<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i312qdf_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i312qdf_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:palette-solid" /></template>
