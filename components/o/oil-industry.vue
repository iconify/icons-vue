<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/k_4pnabxr.css';
import '../../css/q/q28hijmyi.css';
import '../../css/e/ejn_mibun.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNAHyWfxo"><g class="ufeehvblu"><path class="k_4pnabxr"/><path class="q28hijmyi"/><path class="ejn_mibun"/></g></mask></defs><path mask="url(#SVGNAHyWfxo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:oil-industry" /></template>
