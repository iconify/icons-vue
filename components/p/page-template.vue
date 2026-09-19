<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy-g5sp0v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZZ153dkC"><path class="gy-g5sp0v"/></mask></defs><path mask="url(#SVGZZ153dkC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:page-template" /></template>
