<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4s43wbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4s43wbec primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:microscope-duotone" /></template>
