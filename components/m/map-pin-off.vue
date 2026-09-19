<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/svqy3ml4a.css';
import '../../css/b/b66lsbbtf.css';
import '../../css/l/lap40g3pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="svqy3ml4a"/><path class="b66lsbbtf"/><path class="lap40g3pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:map-pin-off" /></template>
