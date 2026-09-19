<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_c634jky.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhhMGxOsy"><path class="h_c634jky"/></mask></defs><path mask="url(#SVGhhMGxOsy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pinwheel" /></template>
