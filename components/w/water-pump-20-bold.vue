<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l179bincs.css';
import '../../css/p/pd_h9evnz.css';
import '../../css/w/wjynhmb7l.css';
import '../../css/x/xm2_-ibkn.css';
import '../../css/z/zv1--mbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l179bincs"/><path class="pd_h9evnz"/><path class="wjynhmb7l"/><path class="xm2_-ibkn"/><path class="zv1--mbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-pump-20-bold" /></template>
