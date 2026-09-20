<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-ush-fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-ush-fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:treasure-map-line" /></template>
