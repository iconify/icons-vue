<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h3rplhb3u.css';
import '../../css/y/yq1lnbbvu.css';
import '../../css/z/zj-4fifqf.css';
import '../../css/e/ewveombiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h3rplhb3u"/><path class="yq1lnbbvu"/><path class="zj-4fifqf"/><path class="ewveombiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:puzzle" /></template>
