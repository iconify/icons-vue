<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/ls2l-iphu.css';
import '../../css/r/rvcd_fbtv.css';
import '../../css/z/zptexebry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ls2l-iphu"/><path class="rvcd_fbtv"/><path class="zptexebry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-square-reply" /></template>
