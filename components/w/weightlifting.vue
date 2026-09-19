<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/l/lbjs96bea.css';
import '../../css/d/dm_j5gglv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMjWPne7J"><g class="cgga7abld"><path class="lbjs96bea"/><path class="dm_j5gglv"/></g></mask></defs><path mask="url(#SVGMjWPne7J)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:weightlifting" /></template>
