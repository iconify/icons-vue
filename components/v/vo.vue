<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/e/et9jo4i1e.css';
import '../../css/d/dgxwspzud.css';
import '../../css/d/d0nm50b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="et9jo4i1e"/><path class="dgxwspzud"/><path class="d0nm50b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:vo" /></template>
