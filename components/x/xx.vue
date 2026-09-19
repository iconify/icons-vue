<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/m/mm_wv7bbg.css';
import '../../css/r/rvfp6dqbl.css';
import '../../css/d/dnah5ac5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="mm_wv7bbg"/><circle class="rvfp6dqbl"/><path class="dnah5ac5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:xx" /></template>
