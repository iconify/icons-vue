<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/n520vob6w.css';
import '../../css/j/jsik09t_m.css';
import '../../css/z/zfctwcctg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="n520vob6w"/><path class="jsik09t_m"/><path class="zfctwcctg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mailbox" /></template>
