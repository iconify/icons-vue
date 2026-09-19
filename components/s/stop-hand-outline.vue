<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/beiar3v7q.css';
import '../../css/m/mqazv_0vr.css';
import '../../css/p/pp2bascsc.css';
import '../../css/b/byrg7evin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="beiar3v7q"/><path class="mqazv_0vr"/><path class="pp2bascsc"/><path class="byrg7evin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-hand-outline" /></template>
