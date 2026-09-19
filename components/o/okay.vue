<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/scu013tui.css';
import '../../css/j/jbj0_8umw.css';
import '../../css/s/s07a-lb1i.css';
import '../../css/i/ico2rabfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="scu013tui"/><path class="jbj0_8umw"/><path class="s07a-lb1i"/><path class="ico2rabfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:okay" /></template>
