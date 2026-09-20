<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzwt4eysc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzwt4eysc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume-minus" /></template>
