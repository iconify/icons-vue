<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/e/e51ymfbza.css';
import '../../css/g/gwpc3dusx.css';
import '../../css/w/w3dbf5lap.css';
import '../../css/u/uoxpizbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="e51ymfbza"/><path class="gwpc3dusx"/><circle class="w3dbf5lap"/><circle class="uoxpizbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:us-fl" /></template>
