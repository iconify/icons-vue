<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/u9x8qellr.css';
import '../../css/i/i3yq3qbys.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbWq8PeLv"><g class="v3_i3wktz"><path class="u9x8qellr"/><path class="i3yq3qbys"/></g></mask></defs><path mask="url(#SVGbWq8PeLv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:resistor" /></template>
