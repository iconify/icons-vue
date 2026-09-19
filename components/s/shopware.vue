<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz0fn1_w.css';
import '../../css/y/yqacr5idm.css';
import '../../css/a/auwbk5w3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="piz0fn1_w"><path class="yqacr5idm"/><path class="auwbk5w3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:shopware" /></template>
