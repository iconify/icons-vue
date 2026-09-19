<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p4-z36bwq.css';
import '../../css/e/e9to63mfe.css';
import '../../css/k/k1uq304yb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAYheqehd"><g class="ft5dv1b6b"><path class="p4-z36bwq"/><path class="e9to63mfe"/><circle transform="matrix(0 -1 -1 0 10 14)" class="k1uq304yb"/><circle transform="matrix(0 -1 -1 0 16 14)" class="k1uq304yb"/></g></mask></defs><path mask="url(#SVGAYheqehd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:upload-web" /></template>
