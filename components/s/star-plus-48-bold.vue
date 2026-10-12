<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9furfe2z.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/u/u4_rd0b0p.css';
import '../../css/t/tlvvk8-lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9furfe2z"/><path class="hwjgqrbah"/><path class="u4_rd0b0p"/><path class="tlvvk8-lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-plus-48-bold" /></template>
