<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lto4ctpit.css';
import '../../css/h/h-keftbiv.css';
import '../../css/z/z3ko96b0e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeSYLeVnl"><g class="ufeehvblu"><path class="lto4ctpit"/><path clip-rule="evenodd" class="h-keftbiv"/><path class="z3ko96b0e"/></g></mask></defs><path mask="url(#SVGeSYLeVnl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:monitor" /></template>
