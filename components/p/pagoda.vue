<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fr7h38bjf.css';
import '../../css/e/ef6l1eg-m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGyssyseA"><g class="v3_i3wktz"><path class="fr7h38bjf"/><path class="ef6l1eg-m"/></g></mask></defs><path mask="url(#SVGGyssyseA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pagoda" /></template>
