<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/u6omv9ofk.css';
import '../../css/e/e4p8vf7to.css';
import '../../css/g/glovd0xbt.css';
import '../../css/w/w45-n2gzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="u6omv9ofk"/><path class="e4p8vf7to"/><path class="glovd0xbt"/><path class="w45-n2gzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tag-outline" /></template>
