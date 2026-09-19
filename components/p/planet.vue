<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/u3yqhguoj.css';
import '../../css/v/van1pxdhn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPzpkEcud"><g class="v3_i3wktz"><path class="u3yqhguoj"/><path class="van1pxdhn"/></g></mask></defs><path mask="url(#SVGPzpkEcud)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:planet" /></template>
