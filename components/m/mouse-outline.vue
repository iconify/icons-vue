<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rtl266vsv.css';
import '../../css/g/gfy16v_7s.css';
import '../../css/j/jda74guyc.css';
import '../../css/j/jie-tb2md.css';
import '../../css/k/k5mgq9bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="mouse-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="rtl266vsv"/><path class="gfy16v_7s"/><path clip-rule="evenodd" class="jda74guyc"/><path clip-rule="evenodd" class="jie-tb2md"/><path clip-rule="evenodd" class="k5mgq9bkd"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:mouse-outline" /></template>
