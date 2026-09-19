<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/m/mez_4wb6c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMGRJObUH"><g class="v1_swcb_o"><circle class="kb9zbkb1z"/><circle class="mez_4wb6c"/></g></mask></defs><path mask="url(#SVGMGRJObUH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:radio-two" /></template>
