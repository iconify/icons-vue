<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8r095um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="es8r095um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:redo" /></template>
