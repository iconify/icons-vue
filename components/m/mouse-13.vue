<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/loci0ub5e.css';
import '../../css/q/qx4gc400j.css';
import '../../css/f/fr15c8b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="loci0ub5e"/><path class="qx4gc400j"/><path class="fr15c8b3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-13" /></template>
