<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/z/z5oavtbwc.css';
import '../../css/i/ic94bsbss.css';
import '../../css/s/sw_zfibgl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGN8BMLZAA"><g class="ufeehvblu"><path class="z5oavtbwc"/><path class="ic94bsbss"/><path class="sw_zfibgl"/></g></mask></defs><path mask="url(#SVGN8BMLZAA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:map-distance" /></template>
