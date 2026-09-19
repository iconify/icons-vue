<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/ijbv10b3u.css';
import '../../css/z/zyit0rs6g.css';
import '../../css/z/z7nlpshuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijbv10b3u"/><path class="zyit0rs6g"/><path class="z7nlpshuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:traffic-jam-02" /></template>
