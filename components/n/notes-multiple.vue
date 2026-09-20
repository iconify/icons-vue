<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hup2v_9xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hup2v_9xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:notes-multiple" /></template>
