<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/gyuogtbyx.css';
import '../../css/t/twu1eqbwq.css';
import '../../css/s/sgoo-oy7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="gyuogtbyx"/><circle class="twu1eqbwq"/><path class="sgoo-oy7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:open-an-account" /></template>
