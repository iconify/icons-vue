<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xgfrcogqu.css';
import '../../css/j/jixhl9msz.css';
import '../../css/n/nh05mtbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgfrcogqu"/><path class="jixhl9msz"/><path class="nh05mtbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:payment-02" /></template>
