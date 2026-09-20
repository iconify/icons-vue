<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz9bty_ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz9bty_ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:undo-sharp" /></template>
