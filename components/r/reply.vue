<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cle0dtw2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0dtw2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:reply" /></template>
