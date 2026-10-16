<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmx6sugjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mmx6sugjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:three-phase-48" /></template>
