<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vph1uef-k.css';
import '../../css/v/vghssgbar.css';
import '../../css/w/whlf697ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vph1uef-k"/><path class="vghssgbar"/><path class="whlf697ff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:saturn-02" /></template>
