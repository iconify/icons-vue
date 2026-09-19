<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xsnp0xxat.css';
import '../../css/y/yeslf1b9b.css';
import '../../css/n/ne1xfo68v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="xsnp0xxat"/><path class="yeslf1b9b"/><path class="ne1xfo68v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:safe-box" /></template>
