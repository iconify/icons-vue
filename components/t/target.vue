<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/v/vttvgz3jw.css';
import '../../css/j/jgo86ngtk.css';
import '../../css/q/qvna00d1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="vttvgz3jw"/><path class="jgo86ngtk"/><path class="qvna00d1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:target" /></template>
