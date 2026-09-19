<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pigt72van.css';
import '../../css/l/loci0ub5e.css';
import '../../css/n/n4oalivtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pigt72van"/><path class="loci0ub5e"/><path class="n4oalivtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-14" /></template>
