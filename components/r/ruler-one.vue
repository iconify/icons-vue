<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/d/dn2ahfhkr.css';
import '../../css/f/fwj4nm9qk.css';
import '../../css/t/tcsb_bbip.css';
import '../../css/q/ql5ml_27x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpAjEecUj"><g class="gopnm44um"><path class="dn2ahfhkr"/><path class="fwj4nm9qk"/><path class="tcsb_bbip"/><path class="ql5ml_27x"/></g></mask></defs><path mask="url(#SVGpAjEecUj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ruler-one" /></template>
