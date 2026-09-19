<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/h2kar04zl.css';
import '../../css/g/gwrmm3xbs.css';
import '../../css/f/ft6udiq_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="h2kar04zl"/><path class="gwrmm3xbs"/><circle class="ft6udiq_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shaver-one" /></template>
