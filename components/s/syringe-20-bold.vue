<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzk42qbyr.css';
import '../../css/b/bsr_e2r7t.css';
import '../../css/b/bguuzc2kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tzk42qbyr"/><path class="bsr_e2r7t"/><path class="bguuzc2kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:syringe-20-bold" /></template>
