<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kbip3tbng.css';
import '../../css/b/bc8oa9bat.css';
import '../../css/i/ixmn_u5zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kbip3tbng"/><path class="bc8oa9bat"/><path class="ixmn_u5zn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notebook-01" /></template>
