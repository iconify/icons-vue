<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz0wpbbiw.css';
import '../../css/m/mah8bbc0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz0wpbbiw"/><path class="mah8bbc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pier-48" /></template>
