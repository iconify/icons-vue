<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/enuncybsk.css';
import '../../css/h/hyr8-8bhd.css';
import '../../css/h/ha34b3bre.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRcYkvdtK"><g class="v3_i3wktz"><path class="enuncybsk"/><path class="hyr8-8bhd"/><path class="ha34b3bre"/></g></mask></defs><path mask="url(#SVGRcYkvdtK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:multi-function-knife" /></template>
