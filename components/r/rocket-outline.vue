<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g_yrw5t-e.css';
import '../../css/l/l_mse-bsg.css';
import '../../css/d/dkc_tb-ko.css';
import '../../css/r/r1nix1b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g_yrw5t-e"/><path class="l_mse-bsg"/><path class="dkc_tb-ko"/><path class="r1nix1b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rocket-outline" /></template>
