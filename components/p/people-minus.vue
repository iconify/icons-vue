<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nmhlnubfi.css';
import '../../css/w/whku1ubxh.css';
import '../../css/t/tyczzdbmu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPdwizdKj"><g class="ft5dv1b6b"><path class="nmhlnubfi"/><path clip-rule="evenodd" class="whku1ubxh"/><path class="tyczzdbmu"/></g></mask></defs><path mask="url(#SVGPdwizdKj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-minus" /></template>
