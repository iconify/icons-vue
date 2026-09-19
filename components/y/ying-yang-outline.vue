<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n0wjplb3e.css';
import '../../css/q/qabc2yclt.css';
import '../../css/c/cnnvx2bys.css';
import '../../css/z/z2caz5u3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n0wjplb3e"/><path class="qabc2yclt"/><path class="cnnvx2bys"/><path class="z2caz5u3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ying-yang-outline" /></template>
