<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/co9ks3b9e.css';
import '../../css/i/ixthzbb7f.css';
import '../../css/n/ndry0d1gg.css';
import '../../css/p/pjinpmb7i.css';
import '../../css/f/fvvcnpb5m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwltxlc3i"><g class="ft5dv1b6b"><path class="co9ks3b9e"/><path class="ixthzbb7f"/><path class="ndry0d1gg"/><path class="pjinpmb7i"/><circle class="fvvcnpb5m"/></g></mask></defs><path mask="url(#SVGwltxlc3i)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:nuclear-plant" /></template>
