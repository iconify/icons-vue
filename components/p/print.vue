<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obwtl28pf.css';
import '../../css/k/keushub5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="obwtl28pf"/><path class="keushub5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:print" /></template>
