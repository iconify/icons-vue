<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm_8_wbdg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQJe1xbJd"><path class="jm_8_wbdg"/></mask></defs><path mask="url(#SVGQJe1xbJd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:windows" /></template>
