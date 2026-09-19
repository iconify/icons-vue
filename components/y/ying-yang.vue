<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/e95lwqnoz.css';
import '../../css/z/zx1vphjyn.css';
import '../../css/t/t0u4y_vup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="e95lwqnoz"/><path class="zx1vphjyn"/><path class="t0u4y_vup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ying-yang" /></template>
