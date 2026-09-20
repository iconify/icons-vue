<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pxyg1sb5z.css';
import '../../css/l/lico50vda.css';
import '../../css/v/voojxubbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pxyg1sb5z"/><path class="lico50vda"/><path class="voojxubbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-download" /></template>
