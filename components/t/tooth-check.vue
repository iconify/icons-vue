<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh8dgebiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8dgebiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tooth-check" /></template>
