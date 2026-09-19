<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hgyipz03i.css';
import '../../css/t/to1q24v3e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNFhCWduG"><g class="v3_i3wktz"><path class="hgyipz03i"/><path class="to1q24v3e"/></g></mask></defs><path mask="url(#SVGNFhCWduG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:upside-down-face" /></template>
