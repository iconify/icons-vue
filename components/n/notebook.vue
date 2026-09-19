<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/iaejugcxy.css';
import '../../css/i/idxsszrzn.css';
import '../../css/o/ofdd852ie.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEqx9mcRF"><g class="ufeehvblu"><path class="iaejugcxy"/><path class="idxsszrzn"/><path class="ofdd852ie"/></g></mask></defs><path mask="url(#SVGEqx9mcRF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:notebook" /></template>
