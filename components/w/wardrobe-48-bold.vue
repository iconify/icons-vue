<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir6r4qmdm.css';
import '../../css/l/lfvfo_aeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ir6r4qmdm"/><path class="lfvfo_aeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wardrobe-48-bold" /></template>
