<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svjkzmbvm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDCDRabPH"><path class="svjkzmbvm"/></mask></defs><path mask="url(#SVGDCDRabPH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:navigation" /></template>
