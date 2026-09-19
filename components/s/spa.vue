<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/odqj4ibcr.css';
import '../../css/r/rctv42bmh.css';
import '../../css/d/ddc43f37b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="odqj4ibcr"/><path class="rctv42bmh"/><path class="ddc43f37b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:spa" /></template>
