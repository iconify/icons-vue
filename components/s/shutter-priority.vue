<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/x44bfmbwq.css';
import '../../css/o/ohqv07ktw.css';
import '../../css/a/axc34h-ro.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFeMiPcSA"><g class="ufeehvblu"><path class="x44bfmbwq"/><path class="ohqv07ktw"/><path class="axc34h-ro"/></g></mask></defs><path mask="url(#SVGFeMiPcSA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shutter-priority" /></template>
