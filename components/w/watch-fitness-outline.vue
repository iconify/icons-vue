<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/werlsvbgf.css';
import '../../css/r/rlkfsjbzh.css';
import '../../css/t/tibulpbty.css';
import '../../css/v/vp2v9wbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="werlsvbgf"/><path class="rlkfsjbzh"/><path class="tibulpbty"/><path class="vp2v9wbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:watch-fitness-outline" /></template>
