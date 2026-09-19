<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vgbcb_s.css';
import '../../css/h/ha1017w6s.css';
import '../../css/v/v5ypc0jqx.css';
import '../../css/k/ksbkozbzk.css';
import '../../css/t/tj21xnbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="ha1017w6s"/><path class="v5ypc0jqx"/><path class="ksbkozbzk"/><path class="tj21xnbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:pa-4x3" /></template>
