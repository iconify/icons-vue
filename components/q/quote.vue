<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/q/qb0lggbeh.css';
import '../../css/l/ls-k7fbvx.css';
import '../../css/j/jrxzbpz9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="qb0lggbeh"/><path class="ls-k7fbvx"/><path class="jrxzbpz9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:quote" /></template>
