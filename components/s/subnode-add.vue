<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/ropt4jr0p.css';
import '../../css/y/ygxy_c58d.css';
import '../../css/b/byu0ligoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ropt4jr0p"/><path class="ygxy_c58d"/><path class="byu0ligoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:subnode-add" /></template>
