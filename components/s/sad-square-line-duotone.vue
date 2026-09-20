<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/bx61cb_8u.css';
import '../../css/w/w9s9usgky.css';
import '../../css/w/wbw_ixbrw.css';
import '../../css/y/yad62e0rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="bx61cb_8u"/><path class="w9s9usgky"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sad-square-line-duotone" /></template>
