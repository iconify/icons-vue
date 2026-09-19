<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/ulau1-bvx.css';
import '../../css/y/y6d2unfse.css';
import '../../css/h/hpckf8hlz.css';
import '../../css/e/em19qbc_z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXf2kodIZ"><g class="ufeehvblu"><rect class="ulau1-bvx"/><path class="y6d2unfse"/><path class="hpckf8hlz"/><path class="em19qbc_z"/></g></mask></defs><path mask="url(#SVGXf2kodIZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:picture-album" /></template>
