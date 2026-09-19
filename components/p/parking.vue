<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/frs-1pvcu.css';
import '../../css/r/r77yemz5v.css';
import '../../css/e/edhf98bll.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYAahXcmP"><g class="v3_i3wktz"><path class="frs-1pvcu"/><path class="r77yemz5v"/><path class="edhf98bll"/></g></mask></defs><path mask="url(#SVGYAahXcmP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:parking" /></template>
