<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0v79xv_p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOLMCCemi"><path class="y0v79xv_p"/></mask></defs><path mask="url(#SVGOLMCCemi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:yep" /></template>
