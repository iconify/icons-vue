<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/o/o59f9vbvm.css';
import '../../css/s/s4exkmb7g.css';
import '../../css/r/rnubj6bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="o59f9vbvm"/><path class="s4exkmb7g"/><path class="rnubj6bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:smoke" /></template>
