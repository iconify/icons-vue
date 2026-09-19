<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/h/h2xliqbhm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZiBm8ctK"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="h2xliqbhm"/></g></mask></defs><path mask="url(#SVGZiBm8ctK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:round-socket" /></template>
