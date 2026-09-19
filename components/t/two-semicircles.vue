<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_tzaabbz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCIj2QcHI"><path clip-rule="evenodd" class="h_tzaabbz"/></mask></defs><path mask="url(#SVGCIj2QcHI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:two-semicircles" /></template>
