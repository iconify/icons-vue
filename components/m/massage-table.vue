<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/ipngrjbif.css';
import '../../css/r/r22my0kcs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFf3hjcGv"><g class="v3_i3wktz"><path class="ipngrjbif"/><path class="r22my0kcs"/></g></mask></defs><path mask="url(#SVGFf3hjcGv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:massage-table" /></template>
