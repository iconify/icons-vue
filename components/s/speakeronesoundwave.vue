<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh96yfr3m.css';
import '../../css/b/ba4pmswhb.css';
import '../../css/d/dzb76ub5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zh96yfr3m"/><path class="ba4pmswhb"/><path class="dzb76ub5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speakeronesoundwave" /></template>
