<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs_lo7bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="cs_lo7bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:polyline" /></template>
