<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne19vg9-n.css';
import '../../css/n/n0aw6mhri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ne19vg9-n"/><path class="n0aw6mhri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-horizontal-20-bold" /></template>
