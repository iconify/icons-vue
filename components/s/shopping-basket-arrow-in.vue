<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dt-je9w2i.css';
import '../../css/a/ad6etcbld.css';
import '../../css/w/wd2oux1ap.css';
import '../../css/i/iaurxkbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dt-je9w2i"/><path class="ad6etcbld"/><path class="wd2oux1ap"/><path class="iaurxkbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-basket-arrow-in" /></template>
