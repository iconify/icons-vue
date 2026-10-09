<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_z88zi0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_z88zi0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-48-bold" /></template>
