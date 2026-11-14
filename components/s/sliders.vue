<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/e/ertbex__b.css';
import '../../css/z/z2w-83bda.css';
import '../../css/l/lrx87p__r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="ertbex__b"/><circle class="z2w-83bda"/><path class="lrx87p__r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:sliders" /></template>
