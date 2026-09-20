<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dft5_h09g.css';
import '../../css/j/jzfqtdbbl.css';
import '../../css/q/q9cwh3bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dft5_h09g"/><path class="jzfqtdbbl"/><path class="q9cwh3bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-2-filled" /></template>
