<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u470c7btl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIsYipbDd"><path class="u470c7btl"/></mask></defs><path mask="url(#SVGIsYipbDd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:three" /></template>
