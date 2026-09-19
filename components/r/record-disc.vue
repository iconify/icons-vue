<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/n/ngg2od8ep.css';
import '../../css/u/ueh3d4bls.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXGQDjeHX"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="ngg2od8ep"/><path class="ueh3d4bls"/></g></mask></defs><path mask="url(#SVGXGQDjeHX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:record-disc" /></template>
