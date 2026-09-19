<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2_6ab4it.css';
import '../../css/e/e8i0a8b0w.css';
import '../../css/e/e7ehw2nvg.css';
import '../../css/p/pd98uok3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="n2_6ab4it"/><path class="e8i0a8b0w"/><path class="e7ehw2nvg"/><circle class="pd98uok3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rabbit-zodiac" /></template>
