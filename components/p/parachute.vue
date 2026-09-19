<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gh28gsjwe.css';
import '../../css/f/fm_ve5bbr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjj1J1bLL"><g class="v3_i3wktz"><path class="gh28gsjwe"/><path class="fm_ve5bbr"/></g></mask></defs><path mask="url(#SVGjj1J1bLL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:parachute" /></template>
