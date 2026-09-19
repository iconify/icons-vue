<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/itmrxab9d.css';
import '../../css/v/vx5dnby3x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRaVXKb6x"><g class="v3_i3wktz"><path class="itmrxab9d"/><path class="vx5dnby3x"/></g></mask></defs><path mask="url(#SVGRaVXKb6x)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:thumbs-down" /></template>
