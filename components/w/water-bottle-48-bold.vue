<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5y_4mbdq.css';
import '../../css/g/gdcg3vxtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5y_4mbdq"/><path class="gdcg3vxtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-bottle-48-bold" /></template>
