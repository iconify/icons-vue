<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/z/z79vt_8gf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtZ24adzH"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="z79vt_8gf"/></g></mask></defs><path mask="url(#SVGtZ24adzH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:smiling-face-with-squinting-eyes" /></template>
