<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng_19u0xj.css';
import '../../css/e/ee19msoje.css';
import '../../css/a/a10r67bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ng_19u0xj"/><path class="ee19msoje"/><path class="a10r67bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tile-48" /></template>
