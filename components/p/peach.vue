<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_40brb9k.css';
import '../../css/g/gm22ybcwr.css';
import '../../css/y/ykwl75vcb.css';
import '../../css/d/dyfh76b9p.css';
import '../../css/o/of830sbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_40brb9k"/><path class="gm22ybcwr"/><path class="ykwl75vcb"/><path class="dyfh76b9p"/><path class="of830sbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:peach" /></template>
