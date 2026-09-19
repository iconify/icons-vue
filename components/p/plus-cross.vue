<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6_q3wbbu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG55kMGW2R"><path class="v6_q3wbbu"/></mask></defs><path mask="url(#SVG55kMGW2R)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:plus-cross" /></template>
