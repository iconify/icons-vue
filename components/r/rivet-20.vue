<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtkkymsak.css';
import '../../css/p/p3c5m7b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gtkkymsak"/><path class="p3c5m7b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rivet-20" /></template>
