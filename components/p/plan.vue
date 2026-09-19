<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/l/ljmw41jut.css';
import '../../css/t/tgf1jxbcb.css';
import '../../css/h/hz2zgmbpt.css';
import '../../css/h/hu_nuxbxh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwLFWJeod"><g class="rohhhzb0l"><path class="ljmw41jut"/><path class="tgf1jxbcb"/><path class="hz2zgmbpt"/><path class="hu_nuxbxh"/></g></mask></defs><path mask="url(#SVGwLFWJeod)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:plan" /></template>
