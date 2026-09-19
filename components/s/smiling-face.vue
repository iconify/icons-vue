<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/w/wepz3acte.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGx7qjRuYJ"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="wepz3acte"/></g></mask></defs><path mask="url(#SVGx7qjRuYJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:smiling-face" /></template>
