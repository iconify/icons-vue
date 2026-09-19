<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/j/j4cvtu_gj.css';
import '../../css/k/kagyhebbk.css';
import '../../css/p/p6kiyzb2b.css';
import '../../css/o/o2ilxycix.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvk1SqcgB"><g class="hv130ab-t"><path class="j4cvtu_gj"/><path class="kagyhebbk"/><circle class="p6kiyzb2b"/><path class="o2ilxycix"/></g></mask></defs><path mask="url(#SVGvk1SqcgB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:permissions" /></template>
