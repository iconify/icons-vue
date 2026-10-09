<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppm3_br9v.css';
import '../../css/r/rh3ta1ono.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppm3_br9v"/><path class="rh3ta1ono"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-up-48" /></template>
