<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/ycpx6cc1w.css';
import '../../css/d/dpom0hb5y.css';
import '../../css/p/pbm76tdaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ycpx6cc1w"/><path class="dpom0hb5y"/><path class="pbm76tdaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:video-ai" /></template>
