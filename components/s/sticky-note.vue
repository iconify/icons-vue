<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpmo-6vfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fpmo-6vfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sticky-note" /></template>
