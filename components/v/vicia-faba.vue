<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sdoteibvg.css';
import '../../css/m/mcdf-5f6l.css';
import '../../css/b/b1f263bkh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvzxhLcCT"><g class="ufeehvblu"><path class="sdoteibvg"/><path class="mcdf-5f6l"/><path class="b1f263bkh"/></g></mask></defs><path mask="url(#SVGvzxhLcCT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:vicia-faba" /></template>
