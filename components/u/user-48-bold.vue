<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftb-bce_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftb-bce_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-48-bold" /></template>
