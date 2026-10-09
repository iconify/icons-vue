<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faamz_bdw.css';
import '../../css/u/uv8trf44e.css';
import '../../css/b/bswze6tia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="faamz_bdw"/><path class="uv8trf44e"/><path class="bswze6tia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-star-48-bold" /></template>
