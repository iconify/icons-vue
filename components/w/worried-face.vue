<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/p/ppz5gobfv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGv7bUUcrw"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="ppz5gobfv"/></g></mask></defs><path mask="url(#SVGv7bUUcrw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:worried-face" /></template>
