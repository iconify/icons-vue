<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj8gq3bcg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTuN6OeRa"><path class="jj8gq3bcg"/></mask></defs><path mask="url(#SVGTuN6OeRa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:star" /></template>
