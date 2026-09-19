<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gjdc2nvab.css';
import '../../css/w/wb4hhokrb.css';
import '../../css/e/esa11jb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="gjdc2nvab"/><path class="wb4hhokrb"/><path class="esa11jb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:route" /></template>
