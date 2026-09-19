<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/w/whkdn_tzm.css';
import '../../css/z/zil4b_b8y.css';
import '../../css/g/ggi7dz0kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="utf5_xbzs"/><path class="whkdn_tzm"/><path class="zil4b_b8y"/><path class="ggi7dz0kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:messages" /></template>
