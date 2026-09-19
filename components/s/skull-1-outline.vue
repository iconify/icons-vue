<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r67ml6b6q.css';
import '../../css/a/a06xhab8s.css';
import '../../css/u/ukg_o6trj.css';
import '../../css/p/p89beacfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r67ml6b6q"/><path class="a06xhab8s"/><path class="ukg_o6trj"/><path class="p89beacfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:skull-1-outline" /></template>
