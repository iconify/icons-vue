<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vey1dxbgo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpGmnzbRE"><path class="vey1dxbgo"/></mask></defs><path mask="url(#SVGpGmnzbRE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:renault" /></template>
