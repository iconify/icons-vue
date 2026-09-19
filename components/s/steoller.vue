<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jm4auib8w.css';
import '../../css/j/jdwxqt97w.css';
import '../../css/t/twqevhb_f.css';
import '../../css/v/vhpw_xe2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jm4auib8w"/><circle class="jdwxqt97w"/><circle class="twqevhb_f"/><path class="vhpw_xe2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:steoller" /></template>
