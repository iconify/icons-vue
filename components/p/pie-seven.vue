<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/n/ncr1c0vah.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpVXoBceu"><g class="aql7dnt-u"><circle class="kb9zbkb1z"/><path class="ncr1c0vah"/></g></mask></defs><path mask="url(#SVGpVXoBceu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pie-seven" /></template>
