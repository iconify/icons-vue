<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p2iw4076h.css';
import '../../css/t/teso3ibks.css';
import '../../css/e/enth-ja-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2iw4076h"/><path class="teso3ibks"/><path class="enth-ja-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-exchange-02" /></template>
