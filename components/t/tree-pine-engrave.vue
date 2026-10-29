<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rethg_bnn.css';
import '../../css/g/guep-fzel.css';
import '../../css/z/z_9w-cekl.css';
import '../../css/b/b33sfbyeh.css';
import '../../css/q/qxnk23bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rethg_bnn wm-k"/><path class="guep-fzel wm-a"/><path class="wm-shadow z_9w-cekl"/><path class="b33sfbyeh wm-k"/><path class="qxnk23bzr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-pine-engrave" /></template>
