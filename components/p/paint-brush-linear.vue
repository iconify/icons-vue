<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxiyvi2in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxiyvi2in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-linear" /></template>
