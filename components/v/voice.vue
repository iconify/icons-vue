<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/k9anlbbxt.css';
import '../../css/h/h2x2yzbat.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGI0ofmUkm"><g class="v3_i3wktz"><rect class="k9anlbbxt"/><path class="h2x2yzbat"/></g></mask></defs><path mask="url(#SVGI0ofmUkm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:voice" /></template>
