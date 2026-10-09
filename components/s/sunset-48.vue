<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-taz-bdu.css';
import '../../css/f/fkg5rrbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-taz-bdu"/><path class="fkg5rrbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunset-48" /></template>
