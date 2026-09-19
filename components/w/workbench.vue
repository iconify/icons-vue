<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/q/qixp1lbnf.css';
import '../../css/f/fic7ufbru.css';
import '../../css/y/y-6hrkbuj.css';
import '../../css/s/sx82wswwc.css';
import '../../css/d/d6rcm1bot.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGICZWIcaL"><g class="ufeehvblu"><path class="qixp1lbnf"/><path class="fic7ufbru"/><path class="y-6hrkbuj"/><path class="sx82wswwc"/><path class="d6rcm1bot"/></g></mask></defs><path mask="url(#SVGICZWIcaL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:workbench" /></template>
